# Angle arguments

The angle argument is used to represent the _yaw_ (horizontal) angle in degrees. The value returned from this argument range from -180.0 (inclusive) to 180 (exclusive), with -180.0 being due north:

\begin{align}
-1&80.0 \\\\
&\hspace{0.1em}N \\\\
&\uparrow \\\\
90.0\ W \leftarrow &\hspace{0.75em}\rightarrow E\  -90.0 \\\\
&\downarrow \\\\
&\hspace{0.2em}S \\\\
&0.0 \\\\
\end{align}

The `~` notation can be used to specify a rotation relative to the executor's yaw angle.

<div class="warning">

**Note:**

The `AngleArgument` is only supported in Minecraft versions 1.16.2 and later, meaning it _will not work_ on Minecraft versions 1.16 or 1.16.1. This is due to the fact that Minecraft added the time argument in 1.16.2. Attempting to use the `AngleArgument` on an incompatible version will throw aa `AngleArgumentException`.

</div>