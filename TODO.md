# Fix API Key Validation Endpoint

## Steps:
- [x] Step 1: Create server/routes/validate-key.ts with validateKey handler for /api/validate-key
- [x] Step 2: Update server/index.ts to import and add app.post('/api/validate-key', validateKey)
- [x] Step 3: Update api/index.ts to import and add app.post('/api/validate-key', validateKeyHandlers.validateKey)
- [x] Step 4: Test by restarting dev server and inserting Groq API key in UI
- [ ] Step 5: Complete task

Current: Step 4 - Test the fix

