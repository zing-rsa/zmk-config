Hi, beginner tinkerer here. I used to use an AutoHotKey script to bind `alt`+`pg_down` to send 15 down arrow keystrokes, and vice versa for `alt`+`pg_up`.
```
!PgUp::Send {Up 15}
!PgDn::Send {Down 15}
```
This put the cursor 15 lines down/up immediately, and worked exactly how you would imagine a 'mini-pagedown' would work.

Now I'm trying to bake this into my Corne with ZMK(so I can use it on PC's without my AHK config), but unsure of the best way. I've tried a macro with: 

```
bindings  = <&macro_tap &kp DOWN &kp DOWN &kp DOWN .... (15 of these)
```

But this results in the cursor progressively moving down the page, similar to what it looks like when you hold the arrow key. This is presumably the intended behavior because it's a sequence of presses. Is there a better approach to replicate my AHK behavior? Thanks!