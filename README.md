# Door2demo


A five-screen, ten-minute permission story inspired by Okta Managed MCP Server.

**This is a scripted simulation.** It uses a fictional profile and local state. It does not connect to Okta, use an API token, or produce live tenant evidence.

## Present

1. Intro (1 min): ask whether the same request will work with both connections.
2. Read-only (2 min): Try the request, review it, and run the simulation. The change is blocked.
3. Edit access (3 min): try the same request, run it, then Check profile. Sales changes to Engineering.
4. Results (2 min): compare the two simulated outcomes.
5. Close (2 min): discuss useful actions with controlled access. Restart demo resets the sample data.

Both connections are preconfigured. No login or tenant setup is required by the simulator. AE and SE buttons change explanation depth only.

## Run locally

Serve this folder with a static server, for example `python3 -m http.server 8000`, then open http://localhost:8000. ES modules need HTTP hosting.

## GitHub Pages

Use Settings > Pages > Deploy from a branch > main > / (root). All URLs are relative, so the project works at a repository subpath.

## Check

Run `node check-simulator.mjs` (repository root layout) or `node scripts/check-simulator.mjs` in the full Sites source checkout.

## Product reference

https://help.okta.com/mcp/en-us/content/topics/mcpserver/mcpserver.htm

Real authorization also depends on operator permissions and resource state. The two sample connections illustrate scope-based access; they do not replace a live product test.

[Download the one-page presenter guide](MCP_Dojo_10_Minute_Guide.pdf)
