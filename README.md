# PETadex index repo

## [PETAdexR](https://github.com/ababaian/petadexR)
`PETadexR` [[link]](https://github.com/ababaian/petadexR) provides `R` based data exploration and analysis tools for plastic‑degrading enzyme sequences. Leveraging petabase‑scale computational biology and high‑throughput functional genomics, PETadexR helps bioinformaticians and biologists identify, visualize, and prioritize novel PETase homologs for experimental validation.

## [PETadex.io](https://github.com/ababaian/petadex.io/) [Under construction]
`PETadex.io` [[link]](https://github.com/ababaian/petadex.io/) is the repository for the `PETadex website.

## `PETadex` Bucket (s3://petadex/)

`PETadex-logan` sequences are hosted on S3, accessible via `aws cli`. All ORFs

```
s3://petadex/logan
├── petadex.logan.all_orfs.v1.fa.zst (120.3 GiB)
├── petadex.logan.enz.v1.fa.zst (18.6 GiB)
└── petadex.logan.seq.v1.fa.zst (61.4 GiB)
```
