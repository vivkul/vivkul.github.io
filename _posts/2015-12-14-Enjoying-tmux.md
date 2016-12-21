---
layout: post
title:  "Enjoying tmux"
comments: true
category: Dev
---

#### tmux is a terminal multiplexer which is very efficient system to use while working through command line. Following are few of the helpful commands that will bring command in life.

~~~~
<h4>	tmux new -s vivkul #creates a new tmux session named vivkul
	tmux ls #shows all the tmux sessions
	tmux a -t vivkul #attaches the tmux session vivkul
	ctrl-b " #creates horizontal split
	ctrl-b up/down #jump the horizontal split
	ctrl-b ctrl-up/down #changes the horizontal split size
	ctrl-b % #creates vertical split
	ctrl-b left/right #jump the vertical split
	ctrl-b ctrl-left/right #changes the vertical split size
	ctrl-b [ #To navigate up and down the current session
	q #to exit up-down
	ctrl-b x #kills the split/tmux session
	ctrl-b d #detaches the tmux session
</h4>
~~~~
