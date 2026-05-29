# Reference Pattern: Secure Firebase Auth Layout

## Implementation Steps
1. **Initialization:** Secure client-side Firebase app initialization using environment variables.
2. **Context Provider:** Wrap app root in an authentication context tracking the state of `onAuthStateChanged`.
3. **API Session Verification:** Send the Firebase ID token in request headers (`Authorization: Bearer <token>`).
4. **Server Middleware:** Verify the ID token using the admin SDK `admin.auth().verifyIdToken(token)`. Reject immediately if expired.
