# Verification

Measured results for Crop Compliant.

Every figure came from running the software while the data room was prepared. None of it is copied
out of a document, and each figure is reproducible by a buyer from the delivered files.

---

## Results

| Measure | Value |
|---|---|
| Tests passing | 142 |
| Tests failing | 0 |
| Tests skipped | 0 |

## Worth knowing

The data room flags two documents to read before the rest, including a deadline-data position. A buyer should start there.

## How this was produced

The software was run from the delivered files. Where a product ships with an installer, the
installer was built. Where a product declares a type check or a build step, both were run. Test
counts are the totals reported by the products' own test commands.

## What is not claimed

A verification record that lists only passes is not a verification record. The package's
open-items document lists every known gap, and it is part of the data room rather than something
a buyer has to discover. Where a test command did not run, where a path went unexercised, or
where behaviour at scale is unproven, the data room says so plainly.

That document is available under a signed non-disclosure agreement, together with the full
verification record and the provenance file. See [ACQUISITION.md](ACQUISITION.md).
