# Parser Node Contribution

Current responsibilities:

- command parsing
- extracting shape information
- extracting size information
- topic communication testing
- validating parser outputs

Current parser workflow:

speech text
→ shape extraction
→ size extraction
→ structured command generation
→ publish to planner node

Example:

Input:
"draw a small triangle"

Parsed output:
shape = triangle
size = small
