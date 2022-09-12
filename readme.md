# Test project

 - implementing beer demo by datafold
 - including elementary package
 - including keboola target runner

## Setup

### Setup Check

`dbt run -t kbc_dev_dbt_beer  --profiles-dir .`

### Setup Elementary

`dbt run --select elementary -t kbc_dev_dbt_beer  --profiles-dir .`

## Run

`dbt run -t kbc_dev_dbt_beer  --profiles-dir .`