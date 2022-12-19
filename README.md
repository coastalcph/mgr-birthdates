# Date Recognition in Historical Parish Records

This repository contains a dataset of birthdates from Danish parish records. It is described in our corresponding ICFHR 2022 paper titled [*Date Recognition in Historical Parish Records*](https://link.springer.com/chapter/10.1007/978-3-031-21648-0_4).

## Repository Structure
We provide a dataset of segmented birthdates under [data/birthdate](data/birthdate) and a dataset of segmented row IDs under [data/row_id](data/row_id). Each dataset is split into train, validation, and test folders. The test folder is further split into easy, average, and difficult folders, as described in our paper. Each folder contains images and a `labels.csv` file that maps from filenames to labels.


## Citation

If you used this dataset in your own work, please cite our work as follows:

```bibtex
@inproceedings{cabello-etal-2022-mgr,
    author="Piqueras, Laura Cabello
    and Fierro, Constanza
    and Lotz, Jonas F.
    and Rust, Phillip
    and Rommedahl, Joen
    and Due, Jeppe Klok
    and Igel, Christian
    and Elliott, Desmond
    and Pedersen, Carsten B.
    and Salazar, Israfel
    and S{\o}gaard, Anders",
    editor="Porwal, Utkarsh
    and Forn{\'e}s, Alicia
    and Shafait, Faisal",
    title="Date Recognition in Historical Parish Records",
    booktitle="Frontiers in Handwriting Recognition",
    year="2022",
    publisher="Springer International Publishing",
    address="Cham",
    pages="49--64",
    isbn="978-3-031-21648-0"
}
```