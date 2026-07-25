# sql-data-projects

SQL scripts from my data analytics portfolio. Two standalone practice files, not a packaged product.

## What's in this repo

| File | What it does | Dialect notes |
|---|---|---|
| `nashville_housing_data_cleaning.sql` | Cleans Nashville housing sales data: standardizes sale dates, fills missing property addresses via self-join on ParcelID, splits address fields, handles sold-as-vacant values, removes duplicates, drops unused columns | Written against SQL Server style (`ISNULL`, `CONVERT`, three-part names like `SQLProject.dbo.NashvilleHousing`) |
| `grocery_store_database_with_stats.sql` | Builds a small grocery `store` table, inserts sample items, then runs price/section aggregates and popularity ranking | Simple SQL (`CREATE TABLE`, `INSERT`, `AVG`, `ORDER BY`, `LIMIT`) |

## What this is not

- Not healthcare SQL (the Nashville file is real-estate housing data)
- Not Power BI, Tableau, or Excel work (those live in other repos / the live portfolio)
- Not a reusable library or database product

## Related

- Live portfolio write-ups: [andre-weissmann-portfolio.pplx.app](https://andre-weissmann-portfolio.pplx.app)
- Portfolio content (JSON + dashboard files): [andre-portfolio-content](https://github.com/Andre-Weissmann/andre-portfolio-content)
- Flagship product work: [dataglow](https://github.com/Andre-Weissmann/dataglow)

## Author

**Andre Weissmann** · Chicago · Data analyst
