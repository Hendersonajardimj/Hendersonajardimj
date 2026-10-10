# Josh Henderson-Jardim

I build tools for reading, learning, and practical workflows. My work includes web apps, native Mac apps, and integrations for small businesses. I develop with coding agents.

[Project stories and demos](https://hendeaux.dev/)

## Things I’m building

### Read Along

A reader that keeps text and narration together. The text highlights as the recording plays, and choosing a word moves playback to that point.

The web tool checks text and timing data and stores them with the audio as a local artifact. The Mac generates narration on the device, labels its word timings as estimated, and publishes a completed package to a selected shared folder. The iPhone and iPad companion validates and downloads that package into its own storage for playback and saved progress. These are development builds, with no public native release claimed.

The public sample includes the shared Swift bundle validator and its failure tests, alongside the small browser timing example. The validator checks hashes, exact text ranges and complete playable audio before committing a local copy.

[Read Along story and demo](https://hendeaux.dev/projects/read-along) · [Public source](https://github.com/Hendersonajardimj/readalong-core) · [Swift validator](https://github.com/Hendersonajardimj/readalong-core/blob/main/companion/ReadAlongKit/Sources/ReadAlongKit/ReadAlongBundle.swift) · [Failure tests](https://github.com/Hendersonajardimj/readalong-core/blob/main/companion/ReadAlongKit/Tests/ReadAlongKitTests/ReadAlongBundleTests.swift)

### Watch Party

A native Mac watch-party app with synchronized playback and chat. Its SwiftUI clients coordinate through a Rust service.

[Watch Party story](https://hendeaux.dev/projects/watch-party)

## Selected client work

- [Post Grad Project](https://hendeaux.dev/work/post-grad-project): coaching-call workflows and tools for reviewing video edits.
- [King MLS](https://hendeaux.dev/work/king-mls): listing-data integration, a client’s property-ranking rules, and Google Sheets output.
- [FUTRSPORT](https://hendeaux.dev/work/futrsport): a custom Shopify storefront theme built on Dawn.

These links lead to public project stories. Client code and data stay private.

## Working with agents

Coding agents are part of my development workflow. For each code example, I aim to make the problem, implementation choices, agent contributions, and current limitations clear.
