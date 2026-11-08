# ClassicBubbles Lab — isolated iOS package build

This CI-only branch builds the standalone ClassicBubbles diagnostic application.
It is not a change to the Transformers game. Do not merge this branch into main.

The two base64 parts reconstruct the complete, SHA-256-verified developer source
archive; CI then compiles both native ARM64 executables and verifies the .deb.
Package ID: com.iammrmikeman.classicbubbles. Sileo-only deployment.

Source archive SHA-256:
b11ac84dc5c63860b3bf189e3fec95efcc9c7133b2187513d4194f877dde81b8

Compilation and offline validation are not on-device testing. The user must test
installation, app launch, diagnostics and report sharing on the iPhone XR.
