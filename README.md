# sca-vuln-small

⚠️ **Intentionally vulnerable test repository (small set).**

A deliberately small set of outdated dependencies with known CVEs (~10–20 total),
for testing SCA / SBOM vulnerability scanning and false-positive detection with a
manageable finding count. **Do not use these versions in real projects.**

- **Python** (`requirements.txt`) — requests, Jinja2, PyYAML, Flask
- **npm** (`package.json`) — minimist, axios
- **Go** (`go.mod`) — jwt-go, yaml.v2
