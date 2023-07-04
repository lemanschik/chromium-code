# AwesomeOS Components
AwesomeOS has only one single unit called Components they usal get composed out of ECMAScript Modules and do export a single 
Readable Writeable Stream Pair (similar to the concepts of input output) a so called TransformStream

The A Special Kind of Component a Component Manager or higher level component uses the exported Streams of the Sub Component
and connects them to it self or other Components. 

The most outer Component is often called the Boot Component or Init Component. Depending on your existing terminology.
