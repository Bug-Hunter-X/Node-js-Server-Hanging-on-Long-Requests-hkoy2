# Node.js Server Hanging Issue

This repository demonstrates a common issue in Node.js where a server can hang due to long-running synchronous operations blocking the event loop. The provided code simulates a long request which causes the server to become unresponsive.

The solution showcases how to use asynchronous programming to avoid blocking the event loop and make the server responsive even during long-running tasks.