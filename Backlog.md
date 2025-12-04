# Product Backlog
A lightweight, living backlog for solo dev or small team workflows.

---

## 1. Epics / Themes

- Authentication & Session Management  
- Navigation, Layout & UX Shell  
- Documentation & Architecture  

---

## 2. Roadmap (High-Level, Optional)

### Horizon 1 (0–2 months)
- SPA - web
- API

### Horizon 2 (3–6 months)
- Analytics

### Horizon 3 (Future)
- iOS/Android apps
---

## 3. Backlog / Tasks

### 🔐 Authentication & Session Management

- ✅ Deploy authenticated navigation via `AuthButtons` and `UserMenu`, including profile access and sign-out handling.  
- ✅ Guard sensitive views with `ProtectedRoute`, capturing navigation intent and reopening the sign-in modal when needed.  
- ✅ Decode JWT payloads client-side and persist session context in `userVar` for downstream components.  
- token refreshing

### 🧭 Navigation, Layout & UX Shell

- ✅ Centralize modal lifecycle with `ModalProvider`, `ModalManager`, and the portal-backed `Modal` component wrapping the app layout.  

### 📚 Documentation & Architecture

- ✅ Refresh the C4 document to cover authenticated UX, protected routing, and user menu changes.  
- ⬜ Add a Mermaid sequence diagram for the WebAuthn flows and embed it in this file.  
- ⬜ Link client documentation to server-side schema or resolver files to map mutations/queries to implementations.  
- ⬜ Create a level-2 container architecture diagram (Mermaid or PlantUML) to illustrate frontend/backend boundaries.  
- ⬜ Document deployment/IaC specifics (CloudFormation, CDK, Terraform) to complement the existing deployment overview.
---

## 🐞 Bugs / Blocking Issues

- ⬜ Example: fix token refresh race condition  
- ⬜ Example: handle missing userVar context on first load  

---

## 📝 Notes / Links

- Architecture Overview → `architecture.md`  
- Key decisions listed inside architecture doc  
- Repo: [link to GitHub / local path]  

---

## Task Marks Legend

- ⬜ Not Started  
- 🚧 In Progress / Working  
- ✅ Done  