Fixed layer making process zombie by calling panic from hookerror, also use `sigkill` instead of `sigterm`