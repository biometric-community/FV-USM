# FV-USM

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FFV--USM-181717?logo=github)](https://github.com/biometric-community/FV-USM)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://blog.eng.usm.my/cvprl/)

**FV-USM** — tbiom catalog packaging for `fv-usm` (vein; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/FV-USM
- **Upstream source**: http://blog.eng.usm.my/cvprl/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `fv-usm` |
| Category | `vein` |
| Access | `register` |
| Upstream homepage | http://blog.eng.usm.my/cvprl/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: USM finger vein; request from CVPRL.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/FV-USM.git
cd FV-USM
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_fv_usm.sh
```

Place licensed archives under `projects/datasets/fv-usm/` (gitignored).

## Dataset structure

```text
FV-USM/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://blog.eng.usm.my/cvprl/
- Packaging: https://github.com/biometric-community/FV-USM/issues
