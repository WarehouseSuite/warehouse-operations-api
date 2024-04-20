# Warehouse Operations Api

- An api responsible for all internal warehouse operations, on a per-location basis.

- Communicates with its corresponding [Warehouse Hub Api](https://github.com/WarehouseSuite/warehouse-operations-api) by receiving jobs, sending out job updates, and sending out inventory updates.

- Carries out warehouse jobs/operations like...

  - Unloading/receiving products into the warehouse system.
  - Putting products away into storage areas.
  - Picking and staging product orders.
  - Loading/shipping products.
  - Auditing.
