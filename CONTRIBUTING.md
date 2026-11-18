# Contributing to WePark Systems

Thank you for contributing cleanly across our services. Please follow these standards across all repositories in `Weparksystems-codebase`:

1. **Branching & Pull Requests**: Create feature/fix branches (`feat/...`, `fix/...`, `chore/...`) and fill out the repository PR checklist before merging to `main`.
2. **Pre-Commit Verification**:
   - **Backend (`cancbackend`)**: Run `node -c` on modified modules; ensure Mongoose schema changes maintain backward compatibility.
   - **Web Portal (`candc-web-portal`)**: Run `npm run build` locally to confirm zero TypeScript or Next.js route build errors.
   - **Mobile (`weparksystemmobile`)**: Run `flutter analyze` with zero errors; update `Info.plist` and `AndroidManifest.xml` whenever adding native capabilities; bump `+N` build numbers in `pubspec.yaml` for releases.
3. **Zero Scratch Files**: Never commit ad-hoc debug scripts, raw error logs, or IDE/AI scratch artifacts to repository roots.
