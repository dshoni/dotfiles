# General
  1 set -g default-terminal "tmux-256color"
  2 set -g base-index 1
  3 setw -g pane-base-index 1
  4 set -g renumber-windows on
  5 set -g history-limit 50000
  6 set -g set-titles on
  7 set -g set-titles-string '#h:#W'
  8
  9 set -g status-position top
 10 set -g status-interval 5
 11 set -g status-left-length 30
 12 set -g status-right-length 50
 13 set -g window-status-separator ""
 14 set -gw automatic-rename on
 15 set -gw automatic-rename-format '#{b:pane_current_path}'
 16 set -g set-titles on
 17 ## set -g set-titles-string '#h:#W'
 18 set -g set-titles-string '#h'
 19
 20 set -g detach-on-destroy off
 21
 22 # Pane controls
 23 bind -N "Kill pane" x kill-pane
 24
 25 # Window navigation
 26 bind -N "Kill window" k kill-window
 27
 28 # Session controls
 29 bind -N "Kill session" K kill-session
 30
 31 # Theme
 32 set -g status-style "bg=default,fg=default"
 33 set -g status-left "#[fg=black,bg=green,bold] #S #[bg=default] "
 34 set -g status-right "#[fg=green]#{?pane_in_mode,COPY ,}#{?client_prefix,PREFIX ,}#{?window_zoomed_flag,ZOOM ,}#[fg=brightblack]#h "
 35 set -g window-status-format "#[fg=brightblack] #I:#W "
 36 set -g window-status-current-format "#[fg=green,bold] #I:#W "
 37 set -g pane-border-style "fg=brightblack"
 38 set -g pane-active-border-style "fg=green"
 39 set -g message-style "bg=default,fg=green"
 40 set -g message-command-style "bg=default,fg=green"
 41 set -g mode-style "bg=green,fg=black"
 42 setw -g clock-mode-colour green
