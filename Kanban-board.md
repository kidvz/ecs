

# Kanban Board
## Backlog
- Add a Mermaid sequence diagram for the WebAuthn flows and embed it in this file.
- Link client documentation to server-side schema or resolver files (when available) to map mutations/queries to implementations.
- Create a level-2 container architecture diagram (Mermaid or PlantUML) to illustrate frontend/backend boundaries.
- Document deployment/IaC specifics (CloudFormation, CDK, Terraform) to complement the existing deployment overview.
## Todo
## In Progress
- —
## Done
- Deploy authenticated navigation via `AuthButtons` and `UserMenu`, including profile access and sign-out handling.
- Guard sensitive views with `ProtectedRoute`, capturing navigation intent and reopening the sign-in modal when needed.
- Decode JWT payloads client-side and persist session context in `userVar` for downstream components.
- Centralize modal lifecycle with `ModalProvider`, `ModalManager`, and the portal-backed `Modal` component wrapping the app layout.
- Refresh the C4 document to cover authenticated UX, protected routing, and user menu changes.
