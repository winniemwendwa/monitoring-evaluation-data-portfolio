# Conservation Agriculture — Year 4 Survey Portfolio

**Prepared for Winnie K. | Excel analysis, dashboards and M&E reporting**

An aggregate-data case study built from a supplied conservation agriculture monitoring survey. It demonstrates reproducible data validation, descriptive analysis and clear reporting. This is an analytical portfolio, not a causal impact evaluation.

![Portfolio preview](figures/Preview.png)

## Selected results

| Measure | Result | Basis |
|---|---:|---|
| Survey records | 219 | Nonempty submissions |
| Reported CA practice | 95.0% | 208 / 219 |
| All three CA principles, full sample | 73.1% | 160 / 219 |
| Recorded average adequate-food months | 10.37 | 219 valid totals; recall-period caveat |
| Recorded 12-month food adequacy | 58.9% | 129 / 219; recall-period caveat |

## Deliverables

- [Visual case study](reports/Portfolio.pdf)
- [Editable case study](reports/Portfolio.docx)
- [Excel dashboard and aggregate tables](reports/Results.xlsx)
- [Methods and limitations](METHODS.md)
- [Upwork portfolio wording](UPWORK_COPY.md)
- CSV tables in `data/` and PNG charts in `figures/`
- `src/analyze.py`: private-source aggregation
- `src/build_portfolio.py`: charts, workbook, PDF and Word generation from aggregate tables

