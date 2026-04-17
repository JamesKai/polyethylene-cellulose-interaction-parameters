# polyethylene-cellulose-interaction-parameters
Interaction Parameters for Paper: "Probing Polyethylene-Cellulose Interfacial Structure with Molecular Simulations"

This repository contains the interaction parameters under the Martini 3 forcefield used for the molecular simulations in the paper: *"Probing Polyethylene-Cellulose Interfacial Structure with Molecular Simulations"*.

## Files Description

The topology files (`10_Cellulose.itp`, `20_Cellulose.itp`, `40_Cellulose.itp`, and `PE.itp`) are generated using [Polyply](https://github.com/marrink-lab/polyply_1.0).

- **`10_Cellulose.itp`**: Topology file for 10-mer cellulose.
- **`20_Cellulose.itp`**: Topology file for 20-mer cellulose.
- **`40_Cellulose.itp`**: Topology file for 40-mer cellulose.
- **`PE.itp`**: Topology file for polyethylene (PE) chains. All interfacial simulations are performed with the same PE chain length (`PE.itp`) with varying cellulose chain lengths (e.g., 10-mer cellulose/PE interface, 20-mer cellulose/PE interface).
- **`martini_v3.0.0.itp`**: Martini 3 forcefield parameter file demonstrating the non-bonded interaction parameters.

## References

All reference data are shown in their respective `.itp` files. If you use these parameters, please cite the following papers according to the files used:

### Cellulose Topologies (`10_Cellulose.itp`, `20_Cellulose.itp`, `40_Cellulose.itp`)
1. Souza, P C T; Alessandri, R; Barnoud, J; Thallmair, S; Faustino, I; Grünewald, F; Patmanidis, I; Abdizadeh, H; Bruininks, B M H; Wassenaar, T A; Kroon, P C; Melcr, J; Nieto, V; Corradi, V; Khan, H M; Domański, J; Javanainen, M; Martinez-Seara, H; Reuter, N; Best, R B; Vattulainen, I; Monticelli, L; Periole, X; Tieleman, D P; de Vries, A H; Marrink, S J; *Nature Methods* **2021**; DOI: [10.1038/s41592-021-01098-3](https://doi.org/10.1038/s41592-021-01098-3)
2. Grunewald, F; Alessandri, R; Kroon, P C; Monticelli, L; Souza, P C; Marrink, S J; *Nature Communications* **2022**; DOI: [10.1038/s41467-021-27627-4](https://doi.org/10.1038/s41467-021-27627-4)
3. Fabian, G; Mats H., P; Elizabeth E., J; Petteri A., V; Melanie, K; Valtteri, V; Travis A., M; Weria, P; Adam J., G; Maarit, K; Mark S. P., S; Paulo C. T, S; Siewert J., M; *JCTC* **2022**; DOI: [10.1021/acs.jctc.2c00757](https://doi.org/10.1021/acs.jctc.2c00757)

### Polyethylene Topology (`PE.itp`)
1. Souza, P C T; Alessandri, R; Barnoud, J; Thallmair, S; Faustino, I; Grünewald, F; Patmanidis, I; Abdizadeh, H; Bruininks, B M H; Wassenaar, T A; Kroon, P C; Melcr, J; Nieto, V; Corradi, V; Khan, H M; Domański, J; Javanainen, M; Martinez-Seara, H; Reuter, N; Best, R B; Vattulainen, I; Monticelli, L; Periole, X; Tieleman, D P; de Vries, A H; Marrink, S J; *Nature Methods* **2021**; DOI: [10.1038/s41592-021-01098-3](https://doi.org/10.1038/s41592-021-01098-3)
2. Grunewald, F; Alessandri, R; Kroon, P C; Monticelli, L; Souza, P C; Marrink, S J; *Nature Communications* **2022**; DOI: [10.1038/s41467-021-27627-4](https://doi.org/10.1038/s41467-021-27627-4)

### Martini 3 Forcefield (`martini_v3.0.0.itp`)
1. Souza, P C T; Alessandri, R; Barnoud, J; Thallmair, S; Faustino, I; Grünewald, F; Patmanidis, I; Abdizadeh, H; Bruininks, B M H; Wassenaar, T A; Kroon, P C; Melcr, J; Nieto, V; Corradi, V; Khan, H M; Domański, J; Javanainen, M; Martinez-Seara, H; Reuter, N; Best, R B; Vattulainen, I; Monticelli, L; Periole, X; Tieleman, D P; de Vries, A H; Marrink, S J; *Nature Methods* **2021**; DOI: [10.1038/s41592-021-01098-3](https://doi.org/10.1038/s41592-021-01098-3)
