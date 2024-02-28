# Deep Scatterplots with DMEPOS provider data

takes a cleaned subset of the publicly available DMEPOS (Medicare Durable Medical Equipment, Devices & Supplies - by Referring Provider and Service) [dataset]([url](https://data.cms.gov/provider-summary-by-type-of-service/medicare-durable-medical-equipment-devices-supplies/medicare-durable-medical-equipment-devices-supplies-by-referring-provider-and-service)https://data.cms.gov/provider-summary-by-type-of-service/medicare-durable-medical-equipment-devices-supplies/medicare-durable-medical-equipment-devices-supplies-by-referring-provider-and-service) from the Centers for Medicare & Medicaid Services and uses deepscatter to visualize relationships between different features in the dataset.

RUNNING INSTRUCTIONS
```
1. python3 -V # requires Python 3.9.x or 3.10.x
2. python3 -m pip install git+https://github.com/bmschmidt/quadfeather
3. quadfeather-test-data 1_000_000
4. quadfeather --files /nomicRobin/dmeAE_balanced.csv --tile_size 50000 --destination tiles
5. npm run dev
```
