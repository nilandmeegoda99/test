### ✅ PR Checklist (Tick all before requesting review)

#### 📄 General
- [ ] PR title is clear, descriptive, and follows naming conventions  
- [ ] Linked to relevant issue(s) or task(s) (`Closes #123`, `Fixes #456`, etc.)  
- [ ] Description clearly explains the purpose and context of the changes  
- [ ] Changes are scoped (single feature/fix per PR)

#### 🔍 Code Quality
- [ ] Code is properly formatted and linted  
- [ ] No commented-out or unused code is left behind  
- [ ] No console logs/debuggers are present in production code  
- [ ] Code is DRY and follows project conventions

#### 🧪 Testing
- [ ] Code has been manually tested and verified  
- [ ] Unit/integration tests added or updated where necessary  
- [ ] All tests are passing locally  
- [ ] Edge cases and potential errors are handled gracefully

#### 💻 Frontend (if applicable)
- [ ] UI changes have been tested on multiple screen sizes (desktop/mobile)  
- [ ] Components are reusable and modular where applicable  
- [ ] Accessibility (a11y) considerations made (e.g., labels, roles)  
- [ ] CSS and JS files are versioned for cache prevention (`?v=1.2.3` or hashed filenames)

#### 🛠️ Backend (if applicable)
- [ ] Proper validation and error handling added  
- [ ] Database migrations (if any) are added and tested  
- [ ] API responses follow standard format and status codes  
- [ ] Secure practices followed (no sensitive data in logs, etc.)

#### 🧾 Documentation
- [ ] Code is commented where necessary for clarity  
- [ ] README/docs updated if needed (e.g., API changes, environment variables)  
- [ ] PR includes screenshots or videos if there are UI changes

#### 🧹 Cleanup
- [ ] Branch is up to date with `main`/`develop`  
- [ ] Verified that no unrelated changes/files are included  
- [ ] PR description includes this checklist and all items are ticked ✅  

