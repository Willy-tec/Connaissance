Général
| Touche       | Description                       | Mode |
|--------------|-----------------------------------|------|
| <C-h>        | Aller à la fenêtre gauche         | n, t |
| <C-j>        | Aller à la fenêtre inférieure     | n, t |
| <C-k>        | Aller à la fenêtre supérieure     | n, t |
| <C-l>        | Aller à la fenêtre droite         | n, t |
| <C-Up>       | Augmenter la hauteur de la fenêtre| n    |
| <C-Down>     | Réduire la hauteur de la fenêtre  | n    |
| <C-Left>     | Réduire la largeur de la fenêtre  | n    |
| <C-Right>    | Augmenter la largeur de la fenêtre| n    |
| <A-j>        | Descendre                         | n, i, v |
| <A-k>        | Monter                            | n, i, v |
| <S-h>        | Buffer précédent                  | n    |
| <S-l>        | Buffer suivant                    | n    |
| [b           | Buffer précédent                  | n    |
| ]b           | Buffer suivant                    | n    |
| <leader>bb   | Changer pour l'autre Buffer       | n    |
| <leader>`    | Changer pour l'autre Buffer       | n    |
| <esc>        | Échapper et effacer hlsearch      | i, n |
| <leader>ur   | Redessiner / effacer hlsearch / mise à jour diff| n |
| n            | Résultat de recherche suivant     | n, x, o |
| N            | Résultat de recherche précédent   | n, x, o |
| <C-s>        | Sauvegarder le fichier            | i, x, n, s |
| <leader>K    | Keywordprg                        | n    |
| <leader>l    | Lazy                              | n    |
| <leader>fn   | Nouveau fichier                   | n    |
| <leader>xl   | Liste des emplacements            | n    |
| <leader>xq   | Liste Quickfix                    | n    |
| [q           | Quickfix précédent                | n    |
| ]q           | Quickfix suivant                  | n    |
| <leader>cf   | Format                            | n, v |
| <leader>cd   | Diagnostics de ligne              | n    |
| ]d           | Diagnostic suivant                | n    |
| [d           | Diagnostic précédent              | n    |
| ]e           | Erreur suivante                   | n    |
| [e           | Erreur précédente                 | n    |
| ]w           | Avertissement suivant             | n    |
| [w           | Avertissement précédent           | n    |
| <leader>uf   | Basculer le format automatique (global) | n |
| <leader>uF   | Basculer le format automatique (buffer)  | n |
| <leader>us   | Basculer l'orthographe            | n    |
| <leader>uw   | Basculer le retour à la ligne     | n    |
| <leader>uL   | Basculer les numéros de ligne relatifs | n |
| <leader>ul   | Basculer les numéros de ligne     | n    |
| <leader>ud   | Basculer les diagnostics          | n    |
| <leader>uc   | Basculer Conceal                  | n    |
| <leader>uh   | Basculer les indices d'incrustation| n  |
| <leader>uT   | Basculer la mise en surbrillance Treesitter| n |
| <leader>gg   | Lazygit (répertoire racine)       | n    |
| <leader>gG   | Lazygit (répertoire courant)      | n    |
| <leader>qq   | Quitter tout                      | n    |
| <leader>ui   | Inspecter Pos                     | n    |
| <leader>L    | Changelog LazyVim                 | n    |
| <leader>ft   | Terminal (répertoire racine)      | n    |
| <leader>fT   | Terminal (répertoire courant)     | n    |
| <c-/>        | Terminal (répertoire racine)      | n    |
| <c-_>        | which_key_ignore                  | n, t |
| <esc><esc>   | Entrer en mode Normal             | t    |
| <C-/>        | Masquer le terminal               | t    |
| <leader>ww   | Autre fenêtre                     | n    |
| <leader>wd   | Supprimer la fenêtre              | n    |
| <leader>w-   | Diviser la fenêtre ci-dessous     | n    |
| <leader>w|   | Diviser la fenêtre à droite       | n    |
| <leader>-   | Diviser la fenêtre ci-dessous      | n    |
| <leader>|   | Diviser la fenêtre à droite        | n    |
| <leader><tab>l | Dernier onglet                  | n    |
| <leader><tab>f | Premier onglet                  | n    |
| <leader><tab><tab> | Nouvel onglet               | n    |
| <leader><tab>] | Onglet suivant                  | n    |
| <leader><tab>d | Fermer l'onglet                 | n    |
| <leader><tab>[ | Onglet précédent                | n    |

LSP
| Touche       | Description                       | Mode |
|--------------|-----------------------------------|------|
| <leader>cl   | Infos Lsp                         | n    |
| gd           | Aller à la Définition             | n    |
| gr           | Références                        | n    |
| gD           | Aller à la Déclaration            | n    |
| gI           | Aller à l'Implémentation          | n    |
| gy           | Aller à la Définition du Type     | n    |
| K            | Survoler                          | n    |
| gK           | Aide à la signature               | n    |
| <c-k>        | Aide à la signature               | i    |
| <leader>
LSP
Clé | Description | Mode
--- | ----------- | ----
`<leader>cl` | Infos Lsp | n
`gd` | Aller à la Définition | n
`gr` | Références | n
`gD` | Aller à la Déclaration | n
`gI` | Aller à l'Implémentation | n
`gy` | Aller à la Définition du Type | n
`K` | Survole | n
`gK` | Aide Signature | n
`<c-k>` | Aide Signature | i
`<leader>ca` | Action Code | n, v
`<leader>cA` | Action Source | n
`<leader>cr` | Renommer | n

bufferline.nvim
Clé | Description | Mode
--- | ----------- | ----
`<leader>bl` | Supprimer les tampons à gauche | n
`<leader>bo` | Supprimer les autres tampons | n
`<leader>bp` | Épingler/Dépingler | n
`<leader>bP` | Supprimer les tampons non épinglés | n
`<leader>br` | Supprimer les tampons à droite | n
`[b` | Tampon Précédent | n
`]b` | Tampon Suivant | n
`<S-h>` | Tampon Précédent | n
`<S-l>` | Tampon Suivant | n

conform.nvim
Clé | Description | Mode
--- | ----------- | ----
`<leader>cF` | Format Langs Injectés | n, v

flash.nvim
Clé | Description | Mode
--- | ----------- | ----
`<c-s>` | Basculer Flash Search | c
`r` | Flash Remote | o
`R` | Recherche Treesitter | o, x
`s` | Flash | n, o, x
`S` | Flash Treesitter | n, o, x

mason.nvim
Clé | Description | Mode
--- | ----------- | ----
`<leader>cm` | Mason | n

mini.bufremove
Clé | Description | Mode
--- | ----------- | ----
`<leader>bd` | Supprimer le Tampon | n
`<leader>bD` | Supprimer le Tampon (Forcé) | n

mini.pairs
Clé | Description | Mode
--- | ----------- | ----
`<leader>up` | Basculer auto paires | n

mini.surround
Clé | Description | Mode
--- | ----------- | ----
`gsa` | Ajouter entourage | n, v
`gsd` | Supprimer entourage | n
`gsf` | Trouver entourage droit | n
`gsF` | Trouver entourage gauche | n
`gsh` | Mettre en surbrillance l'entourage | n
`gsn` | Mettre à jour MiniSurround.config.n_lines | n
`gsr` | Remplacer l'entourage | n

neo-tree.nvim
Clé | Description | Mode
--- | ----------- | ----
`<leader>be` | Explorateur de Tampons | n
`<leader>e` | Explorateur NeoTree (répertoire racine) | n
`<leader>E` | Explorateur NeoTree (cwd) | n
`<leader>fe` | Explorateur NeoTree (répertoire racine) | n
`<leader>fE` | Explorateur NeoTree (cwd) | n
`<leader>ge` | Explorateur Git | n

noice.nvim
Clé | Description | Mode
--- | ----------- | ----
`<c-b>` | Faire défiler vers l'arrière | n, i, s
`<c-f>` | Faire défiler vers l'avant | n, i, s
`<leader>sna` | Noice Tout | n
`<leader>snd` | Dismiss Tout | n
`<leader>snh` | Historique Noice | n
`<leader>snl` | Dernier message Noice | n
`<S-Enter>` | Rediriger Cmdline | c

nvim-notify
Clé | Description | Mode
--- | ----------- | ----
`<leader>un` | Dismiss all Notifications | n

nvim-spectre
Clé | Description | Mode
--- | ----------- | ----
`<leader>sr` | Remplacer dans les fichiers (Spectre) | n

nvim-treesitter
Clé | Description | Mode
--- | ----------- | ----
`<bs>` | Décrémenter la sélection | x
`<c-space>` | Incrémenter la sélection | n

nvim-treesitter-context
Clé | Description | Mode
--- | ----------- | ----
`<leader>ut` | Basculer le contexte Treesitter | n

persistence.nvim
Clé | Description | Mode
--- | ----------- | ----
`<leader>qd` | Ne pas sauvegarder la session courante | n
`<leader>ql` | Restaurer la dernière session | n
`<leader>qs` | Restaurer la session | n

telescope.nvim
Clé | Description | Mode
--- | ----------- | ----
`<leader><space>` | Trouver des fichiers (répertoire racine) | n
`<leader>,` | Changer de tampon | n
`<leader>/` | Grep (répertoire racine) | n
`<leader>:` | Historique des commandes | n
`<leader>fb` | Tampons | n
`<leader>fc` | Trouver le fichier de configuration | n
`<leader>ff` | Trouver des fichiers (répertoire racine) | n
`<leader>fF` | Trouver des fichiers (cwd) | n
`<leader>fr` | Récent | n
`<leader>fR` | Récent (cwd) | n
`<leader>gc` | commits | n
`<leader>gs` | status | n
`<leader>s"` | Registres | n
`<leader>sa` | Commandes auto | n
`<leader>sb` | Tampon | n
`<leader>sc` | Historique des commandes | n
`<leader>sC` | Commandes | n
`<leader>sd` | Diagnostics du document | n
`<leader>sD` | Diagnostics de l'espace de travail | n
`<leader>sg` | Grep (répertoire racine) | n
`<leader>sG` | Grep (cwd) | n
`<leader>sh` | Pages d'aide | n
`<leader>sH` | Groupes de surbrillance de recherche | n
`<leader>sk` | Maps de clés | n
`<leader>sm` | Aller à la marque | n
`<leader>sM` | Pages Man | n
`<leader>so` | Options | n
`<leader>sR` | Reprendre | n
`<leader>ss` | Aller au symbole | n
`<leader>sS` | Aller au symbole (espace de travail) | n
`<leader>sw` | Mot (répertoire racine) | n
`<leader>sW` | Mot (cwd) | n
`<leader>sw` | Sélection (répertoire racine) | v
`<leader>sW` | Sélection (cwd) | v
`<leader>uC` | Thème de couleurs avec prévisualisation | n

todo-comments.nvim
Clé | Description | Mode
--- | ----------- | ----
`<leader>st` | Todo | n
`<leader>sT` | Todo/Fix/Fixme | n
`<leader>xt` | Todo (Trouble) | n
`<leader>xT` | Todo/Fix/Fixme (Trouble) | n
`[t` | Commentaire todo précédent | n
`]t` | Commentaire todo suivant | n

trouble.nvim
Clé | Description | Mode
--- | ----------- | ----
`<leader>xL` | Liste des emplacements (Trouble) | n
`<leader>xQ` | Liste Quickfix (Trouble) | n
`<leader>xx` | Diagnostics du document (Trouble) | n
`<leader>xX` | Diagnostics de l'espace de travail (Trouble) | n
`[q` | Élément trouble/quickfix précédent | n
`]q` | Élément trouble/quickfix suivant | n

vim-illuminate
Clé | Description | Mode
--- | ----------- | ----
`[[` | Référence précédente | n
`]]` | Référence suivante | n

yanky.nvim
Partie de lazyvim.plugins.extras.coding.yanky
Clé | Description | Mode
--- | ----------- | ----
`<leader>p` | Ouvrir l'historique Yank | n
`<p` | Mettre en place et indenter à gauche | n
`<P` | Mettre en place avant et indenter à gauche | n
`=p` | Mettre en place après application d'un filtre | n
`=P` | Mettre en place avant application d'un filtre | n
`>p` | Mettre en place et indenter à droite | n
`>P` | Mettre en place avant et indenter à droite | n
`[p` | Mettre en place indenté avant le curseur (linewise) | n
`[P` | Mettre en place indenté avant le curseur (linewise) | n
`[y` | Faire défiler vers l'avant à travers l'historique Yank | n
`]p` | Mettre en place indenté après le curseur (linewise) | n
`]P` | Mettre en place indenté après le curseur (linewise) | n
`]y` | Faire défiler vers l'arrière à travers l'historique Yank | n
`gp` | Mettre en place le texte yanké après la sélection | n, x
`gP` | Mettre en place le texte yanké avant la sélection | n, x
`p` | Mettre en place le texte yanké après le curseur | n, x
`P` | Mettre en place le texte yanké avant le curseur | n, x
`y` | Yanker le texte | n, x

nvim-dap

Partie de lazyvim.plugins.extras.dap.core
Clé | Description | Mode
--- | ----------- | ----
`<leader>da` | Exécuter avec arguments | n
`<leader>db` | Basculer le point d'arrêt | n
`<leader>dB` | Condition du point d'arrêt | n
`<leader>dc` | Continuer | n
`<leader>dC` | Courir jusqu'au curseur | n
`<leader>dg` | Aller à la ligne (sans exécution) | n
`<leader>di` | Entrer pas à pas | n
`<leader>dj` | Descendre | n
`<leader>dk` | Monter | n
`<leader>dl` | Exécuter le dernier | n
`<leader>do` | Sortir pas à pas | n
`<leader>dO` | Passer au-dessus | n
`<leader>dp` | Pause | n
`<leader>dr` | Basculer REPL | n
`<leader>ds` | Session | n
`<leader>dt` | Terminer | n
`<leader>dw` | Widgets | n

nvim-dap-ui

Partie de lazyvim.plugins.extras.dap.core
Clé | Description | Mode
--- | ----------- | ----
`<leader>de` | Évaluer | n, v
`<leader>du` | Dap UI | n

aerial.nvim

Partie de lazyvim.plugins.extras.editor.aerial
Clé | Description | Mode
--- | ----------- | ----
`<leader>cs` | Aerial (Symboles) | n

telescope.nvim

Partie de lazyvim.plugins.extras.editor.aerial
Clé | Description | Mode
--- | ----------- | ----
`<leader>ss` | Aller au symbole (Aerial) | n

flit.nvim

Partie de lazyvim.plugins.extras.editor.leap
Clé | Description | Mode
--- | ----------- | ----
`f` | f | n, o, x
`F` | F | n, o, x
`t` | t | n, o, x
`T` | T | n, o, x

leap.nvim

Partie de lazyvim.plugins.extras.editor.leap
Clé | Description | Mode
--- | ----------- | ----
`gs` | Sauter depuis les fenêtres | n, o, x
`s` | Sauter en avant vers | n, o,

`S` | Sauter en arrière vers | n, o, x

mini.files

Partie de lazyvim.plugins.extras.editor.mini-files
Clé | Description | Mode
--- | ----------- | ----
`<leader>fm` | Ouvrir mini.files (répertoire du fichier courant) | n
`<leader>fM` | Ouvrir mini.files (cwd) | n

symbols-outline.nvim

Partie de lazyvim.plugins.extras.editor.symbols-outline
Clé | Description | Mode
--- | ----------- | ----
`<leader>cs` | Symbols Outline | n

markdown-preview.nvim

Partie de lazyvim.plugins.extras.lang.markdown
Clé | Description | Mode
--- | ----------- | ----
`<leader>cp` | Aperçu Markdown | n

nvim-dap-python

Partie de lazyvim.plugins.extras.lang.python
Clé | Description | Mode
--- | ----------- | ----
`<leader>dPc` | Debug Class | n
`<leader>dPt` | Debug Method | n

venv-selector.nvim

Partie de lazyvim.plugins.extras.lang.python
Clé | Description | Mode
--- | ----------- | ----
`<leader>cv` | Sélectionner VirtualEnv | n

neotest

Partie de lazyvim.plugins.extras.test.core
Clé | Description | Mode
--- | ----------- | ----
`<leader>to` | Afficher la sortie | n
`<leader>tO` | Basculer le panneau de sortie | n
`<leader>tr` | Exécuter le plus proche | n
`<leader>ts` | Basculer le résumé | n
`<leader>tS` | Stop | n
`<leader>tt` | Exécuter le fichier | n
`<leader>tT` | Exécuter tous les fichiers de test | n

nvim-dap

Partie de lazyvim.plugins.extras.test.core
Clé | Description | Mode
--- | ----------- | ----
`<leader>td` | Debug le plus proche | n

edgy.nvim
 

