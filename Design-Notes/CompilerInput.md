
## members

```
	private final String                           inp;
	private       Ty                               ty;

	private       Maybe<ILazyCompilerInstructions> accept_ci;
	private       File                             dir_carrier;
	private       String                           hash;
```

## design

1. Wants to actually be a `IProgressive` (learn ocaml, and concomitantly unison)
- values change over time, based on internal processing
- manifold/missionary
- Banai Bros...
- https://gitlab.com/elijah-team/documentation/petal-to-the-medal/-/blob/main/ginitiatives/G7.md

2. Now (TODO: provide reference)
- created with `inp`, as specified on command line
- ty is set later
- dir_carrier, accept_ci and hash are set/used in other parts
