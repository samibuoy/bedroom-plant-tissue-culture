
```dataview
TABLE id AS "ID", date_inoculated AS "Inoculation Date", species AS "Species", media_batch AS "Media Recipe", status AS "Status"
FROM "Plant Tissue Culture/Experiments"
WHERE type = "experiment"
SORT date_inoculated DESC
```

```dataview
TABLE id AS "Batch", date_formulated AS "Date Mixed", basal_salt AS "Base", cytokinin_pgr AS "Cytokinin", auxin_pgr AS "Auxin"
FROM "Plant Tissue Culture/Media Batches"
WHERE type = "media"
SORT date_formulated DESC
```