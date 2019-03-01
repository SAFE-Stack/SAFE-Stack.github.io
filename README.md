# SAFE-Stack.github.io
Website for Saturn + Azure + Fable + Elmish aka SAFE-Stack

# Supported SAFE runtimes
Due to the many different combinations of .NET runtimes, F# versions, IDEs and F# Project Types, the following table can be used to quickly identify what runtime stack that are required in order to utilise different versions of the stack.

*Other = Ionide / Rider etc.*

| TFM | F# | IDE | Project Type | Suave? | Azure? | Fable + Elmish? |
|-|-|-|-|-|-|-|
| NET 4.x | F#4.0 | VS2015 | Classic | Yes | Yes | No project support |
| NET 4.x | F#4.1 | VS2017 | Classic | Yes | Yes | No project support |
| NET 4.x | F#4.0 | VS2015 | Classic | Yes | Yes | No project support |
| NET 4.x | F#4.1 | Other | Classic | Yes | Yes | No project support |
| NET 4.x | F#4.1 | Other | Modern | Yes | Yes | Yes |
| NetCore | F#4.1 | VS2017 | Classic | Yes | Storage TP unsupported | No project support |
| NetCore | F#4.1 | VS2017 | Modern | Not yet | Not yet | Not yet |
| NetCore | F#4.1 | Other | Classic | Yes | Storage TP unsupported | No project support |
| NetCore | F#4.1 | Other | Modern | Yes | Storage TP unsupported | Yes |
