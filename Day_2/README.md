- Calculated the length (in km) of Karnataka highways [*national_highways* layer]

- Extracted the features with null values of **_name_** attribute removed [*nh_with_non_null_names* layer]

- Created a spatial join of national highways by district and computed spatial statistics by the **_DISTRICT_** attribute [*national_highways_by_district* layer]

- Formatted the above layer to keep only the **_district_** and **_total_length_** (rounded to integer) attributes [*national_highways_by_district_formatted* layer]


All layers are within the **karnataka.gpkg** file