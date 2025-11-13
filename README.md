# Community Software Facility (CSF) Community Playbook


[![Documentation Status](https://readthedocs.org/projects/csf/badge/?version=latest)](https://csf.readthedocs.io/en/latest/?badge=latest)

This repository was based off of the [NCAR mkdocs template](https://github.com/NCAR/NCAR_mkdocs_template). For instructions on the use of
the template, see [their documentation](https://ncar-mkdocs-template.readthedocs.io/en/latest/getting-started/).

## Get Started
Clone and initialize the repository

```
git clone https://github.com/NCAR/CSF.git
cd CSF
git submodule init
git submodule update --remote
```


Setup a conda environement

```
conda env create -f conda.yaml
conda activate mkdocs
```

Preview local edits

```
mkdocs serve
```

## License

This material is licensed under Creative Commons Attribution ShareAlike 4.0 ([CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)).  You are free to:

- **Share** — copy and redistribute the material in any medium or format for any purpose, even commercially.

- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

- **Attribution** - You must give appropriate credit , provide a link to the license, and indicate if changes were made . You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

- **ShareAlike** - If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
No additional restrictions - You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

See [here](https://creativecommons.org/licenses/by-sa/4.0/legalcode.en) for full details.
