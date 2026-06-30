managed with [chezmoi](https://chezmoi.io)

## What's in here

  | File                                                    | What it configures                                                                    |
  | ------------------------------------------------------- | ------------------------------------------------------------------------------------- |
  | `dot_zshrc`                                             | zsh + Oh My Zsh + fzf + plugins                                                       |
  | `dot_gitconfig.tmpl`                                    | git identity (templated), delta, difftools, signing (opt-in), UCL credential (opt-in) |
  | `private_dot_config/omp/`                               | oh-my-posh prompt (Catppuccin Mocha)                                                  |
  | `private_dot_config/kitty/`                             | kitty terminal                                                                        |
  | `private_dot_config/lazygit/`                           | lazygit                                                                               |
  | `private_dot_config/bat/config`                         | bat theme selection                                                                   |
  | `private_dot_config/git/ignore`, `catppuccin.gitconfig` | global gitignore + delta theme                                                        |
  | `private_dot_config/gh/`                                | gh CLI settings (no auth)                                                             |
  | `private_dot_config/panache/`                           | panache                                                                               |
  | `dot_oh-my-zsh/custom/plugins/opencode/`                | opencode completion plugin                                                            |

## Apply on a new machine

```sh
sh -c "$(curl -fsLS https://get.chezmoi.io)" -- init --apply <github-username>/dotfiles
```
