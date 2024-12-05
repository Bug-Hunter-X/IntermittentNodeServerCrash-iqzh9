# Intermittent Node.js Server Crash

This repository demonstrates a bug causing intermittent crashes in a simple Node.js HTTP server. The server runs without throwing any errors, making debugging challenging.

## Bug Description

A Node.js HTTP server crashes sporadically without providing any error messages or stack traces in the console. This makes identifying the root cause difficult.

## How to Reproduce

1. Clone this repository.
2. Run `node server.js`.
3. Observe that the server may crash at random intervals without any indication.

## Solution

The solution involves adding proper error handling to gracefully manage potential exceptions or resource exhaustion within the server.