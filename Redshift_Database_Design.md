# Database Design

## Creating table and imparting schema using AWS Redshift Serverless 
```
CREATE TABLE public.machine_data (
    machine_timestamp timestamp without time zone,
    machine_manufacturer_id character varying(256),
    line character varying(256),
    line_description character varying(256),
    operator_name character varying(256),
    operator_perno character varying(256),
    machine character varying(256),
    machine_description character varying(256),
    units_target integer,
    wire_tension double precision,
    power_unit integer,
    error_code character varying(256),
    bit_speed double precision,
    temperature double precision,
    units double precision,
    oee double precision,
    defective_count double precision
) DISTSTYLE AUTO;

```

