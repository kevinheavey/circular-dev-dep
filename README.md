# Circular dev-dependencies example

Example repo demonstrating that you can publish
crates with circular dev-dependencies if these dev-dependencies
are path dependencies. If you use workspace dependencies
that contain both versions and paths, you won't be
able to publish.
