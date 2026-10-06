<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

## Application rules
- Keep the portfolio at `/` and the complete CV at `/cv` using TanStack routes, so original navigation and downloads stay intact.
- Define portfolio appearance and reduced-motion-aware opening animations in the global design system, so all screens share consistent tokens.
- Store imported repository media as project-scoped asset pointers, so published images do not depend on another project's storage.
