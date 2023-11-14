
## members

```
	private final String                           inp;
	private       Ty                               ty;

	private       Maybe<ILazyCompilerInstructions> accept_ci;
	private       File                             dir_carrier;
	private       String                           hash;
```

## design

1. Wants to actually be a Progressive
- values change over time, based on internal processing

2. Now
- created with `inp`, as specified on command line
- ty is set later
- dir_carrierm accept_ci and hash are set/used in other parts
