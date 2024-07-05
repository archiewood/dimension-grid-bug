```sql test_data
select 'United States' as "country name", 100 as population union all
select 'Canada', 50
```

<DataTable data={test_data}/>

<DimensionGrid data={test_data}/>

