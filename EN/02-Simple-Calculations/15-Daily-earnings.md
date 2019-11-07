[slide]
# Short with defaults

[live-stream videoId="12345ID" playerType="vimeo" /]

[/slide]

[slide]
# Short
[live-stream language="eN" videoId="12345ID" playerType="vimeo" /]
[/slide]

[slide]
# 1 stream with defaults
[live-stream playerType="vimeo"]
[stream videoId="1231234" /]
[/live-stream]
[/slide]

[slide]
# 1 stream

[live-stream playerType="vimeo"]
[stream videoId="1231234" language="eN" default /]
[/live-stream playerType="vimeo"]

[/live-stream]

[/slide]

[slide]
# Multiple with defaults
[live-stream playerType="vimeo"]
[stream videoId="1231234" /]
[stream videoId="1231234" language="eN2" /]
[/live-stream]
[/slide]

[slide]
# Multiple
[live-stream playerType="vimeo"]
[stream videoId="1231234" language="eN" /]
[stream videoId="1231234" language="eN" default /]
[/live-stream]
[/slide]