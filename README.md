### **💡 tmux Cheat Sheet (From Creating a Session to Killing It) 🚀**  

| **Action** | **Command** |
|------------|------------|
| **Create a New tmux Session** | `tmux` |
| **Create a New Named Session** | `tmux new -s <name>` |
| **List Existing Sessions** | `tmux ls` |
| **Attach to Last Session** | `tmux a` or `tmux attach` |
| **Attach to a Specific Session** | `tmux attach -t <name>` |
| **Detach from a Session (Keep It Running in Background)** | `Ctrl + b`, then `d` |
| **Kill a Specific Session** | `tmux kill-session -t <name>` |
| **Kill All tmux Sessions** | `tmux kill-server` |

### **Managing Windows (Tabs)**
| **Action** | **Command** |
|------------|------------|
| **Create a New Window** | `Ctrl + b`, then `c` |
| **Switch Between Windows** | `Ctrl + b`, then `n` (next) or `p` (previous) |
| **Rename a Window** | `Ctrl + b`, then `,` |
| **Close a Window** | `Ctrl + b`, then `&` |

### **Splitting and Managing Panes**
| **Action** | **Command** |
|------------|------------|
| **Split Vertically (Left & Right)** | `Ctrl + b`, then `%` |
| **Split Horizontally (Top & Bottom)** | `Ctrl + b`, then `"` |
| **Navigate Between Panes** | `Ctrl + b`, then Arrow Keys (←, →, ↑, ↓) |
| **Swap Panes** | `Ctrl + b`, then `{` (swap up) or `}` (swap down) |
| **Resize Pane (Left, Right, Up, Down)** | `Ctrl + b`, then `Ctrl + Arrow Keys` |
| **Make a Pane Fullscreen (Zoom Mode)** | `Ctrl + b`, then `z` |
| **Cycle Through Layouts** | `Ctrl + b`, then `Space` |
| **Move a Pane to a New Window** | `Ctrl + b`, then `!` |
| **Close the Current Pane** | `Ctrl + b`, then `x` (Confirm `y`) |
| **Kill a Specific Pane** | `Ctrl + b`, then `:kill-pane -t <pane-number>` |

### **Exiting and Killing Sessions**
| **Action** | **Command** |
|------------|------------|
| **Detach from tmux (Keep Running in Background)** | `Ctrl + b`, then `d` |
| **Kill the Current Session** | `Ctrl + b`, then `:kill-session` |
| **Kill a Specific Session** | `tmux kill-session -t <name>` |
| **Kill All Running tmux Sessions** | `tmux kill-server` |
| **Exit tmux Completely** | `exit` |

