# Archaeology Knowledge Graph (ArKG) Chile

> An interdisciplinary initiative between Archaeology, Physics, and Computer Science
> that organizes, systematizes, visualizes, and openly distributes archaeological
> dates from Chile.

🌐 [arkg.cl](https://arkg.cl)

---

## What is ArKG?

ArKG organizes archaeological dating data as a **Knowledge Graph** in
[RDF](https://en.wikipedia.org/wiki/Resource_Description_Framework), following
semantic web standards and the FAIR principles (Findable, Accessible,
Interoperable, Reusable). The graph is stored in
[MillenniumDB](https://github.com/MillenniumDB/MillenniumDB), a graph-oriented
database management system developed by the
[IMFD](https://imfd.cl/).

Archaeological dates are treated as **digital heritage**, with a commitment to
durability, preservation, and open access for the entire community.

---

## Project Modules

This repository unifies the project components as Git submodules:

| Module | Repository | Description |
|--------|------------|-------------|
| `docs/` | [ArKG-docs](https://github.com/ArKG-Data/ArKG-docs) | Project documentation, predicate definitions, and Knowledge Graph data |
| `browser/` | [ArKG-Browser](https://github.com/ArKG-Data/ArKG-Browser) | Web application to visually navigate and query the graph ([arkg.cl/graph](https://arkg.cl/graph)) |
| `data/` | [ArKG-Data](https://github.com/ArKG-Data/ArKG-Data) | Dataset of archaeological dates from Chile |
| `pipeline/` | [ArKG-DataPipeline](https://github.com/ArKG-Data/ArKG-DataPipeline) | Data processing and transformation pipeline to RDF format |

---

## Cloning with Submodules

```bash
git clone --recurse-submodules https://github.com/ArKG-Data/ArKG.git
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

---

## Contributing

Contributions are always welcome! To get involved, please reach out at
[roberto.campbell@uc.cl](mailto:roberto.campbell@uc.cl).

---

## License

[ArKG](https://arkg.cl) © 2025 by [ArKG Team](https://github.com/orgs/ArKG-Data/repositories)
is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
