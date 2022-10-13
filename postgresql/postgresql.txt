CREATE SCHEMA staging;
CREATE SCHEMA processing;
CREATE SCHEMA reporting;
CREATE table staging.staging_covid (
country text,
iso_code text,
p_date date,
total_vaccinations int,
people_vaccinated int,
people_fully_vaccinated int,
daily_vaccinations_raw int,
daily_vaccinations int,
total_vaccinations_per_hundred int,
people_vaccinated_per_hundred int,
people_fully_vaccinated_per_hundred int,
daily_vaccinations_per_million int,
vaccines text,
source_name text,
source_website text
);