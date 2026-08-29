# Data dictionary

This file summarizes selected processed/aggregated CSV files included in `data/processed/`.

## `00_need_domain_summary_by_income_region.csv`

Columns:
- `group`
- `need_variable`
- `median_score`
- `group_type`

## `00_scopus_annual_counts.csv`

Columns:
- `year`
- `document_type`
- `n_records`

## `00_scopus_corpus_summary.csv`

Columns:
- `item`
- `value`

## `00_top_food_system_need_index_main.csv`

Columns:
- `iso3`
- `country`
- `region`
- `income_group`
- `population`
- `food_system_need_index_main_min4`
- `food_system_need_index_strict_all5`
- `n_need_axes_available`
- `dominant_need_profile`
- `missing_need_axes`
- `need_food_security_score`
- `need_nutrition_score`
- `need_food_waste_score`
- `need_sustainability_score`
- `need_supply_vulnerability_score`
- `undernourishment_pct`
- `child_stunting_pct`
- `adult_obesity_pct`
- `household_food_waste_kg_capita`
- `household_food_waste_confidence`
- `agrifood_ghg_tco2eq_per_capita`
- `cereal_import_dependency_pct`

## `00_top_food_system_need_index_strict.csv`

Columns:
- `iso3`
- `country`
- `region`
- `income_group`
- `population`
- `food_system_need_index_main_min4`
- `food_system_need_index_strict_all5`
- `n_need_axes_available`
- `dominant_need_profile`
- `missing_need_axes`
- `need_food_security_score`
- `need_nutrition_score`
- `need_food_waste_score`
- `need_sustainability_score`
- `need_supply_vulnerability_score`
- `undernourishment_pct`
- `child_stunting_pct`
- `adult_obesity_pct`
- `household_food_waste_kg_capita`
- `household_food_waste_confidence`
- `agrifood_ghg_tco2eq_per_capita`
- `cereal_import_dependency_pct`

## `03_country_total_ai_food_research_attention_raw.csv`

Columns:
- `iso3`
- `country`
- `ai_food_papers_full_count`
- `ai_food_papers_fractional_count`
- `n_unique_papers`
- `first_year`
- `last_year`
- `region`
- `income_group`
- `population`
- `gdp_current_usd`
- `rd_expenditure_pct_gdp`
- `food_system_need_index_main_min4`
- `food_system_need_index_strict_all5`
- `need_food_security_score`
- `need_nutrition_score`
- `need_food_waste_score`
- `need_sustainability_score`
- `need_supply_vulnerability_score`
- `ai_food_papers_per_million_population_full`
- `ai_food_papers_per_million_population_fractional`
- `ai_food_papers_per_billion_gdp_full`
- `ai_food_papers_per_billion_gdp_fractional`

## `03_country_year_ai_food_research_attention_raw.csv`

Columns:
- `iso3`
- `country`
- `year`
- `ai_food_papers_full_count`
- `ai_food_papers_fractional_count`
- `n_unique_papers`
- `region`
- `income_group`
- `population`
- `gdp_current_usd`
- `rd_expenditure_pct_gdp`
- `food_system_need_index_main_min4`
- `food_system_need_index_strict_all5`
- `need_food_security_score`
- `need_nutrition_score`
- `need_food_waste_score`
- `need_sustainability_score`
- `need_supply_vulnerability_score`
- `ai_food_papers_per_million_population_full`
- `ai_food_papers_per_million_population_fractional`
- `ai_food_papers_per_billion_gdp_full`
- `ai_food_papers_per_billion_gdp_fractional`

## `08_unep_household_food_waste_annex3_extracted.csv`

Columns:
- `unep_region`
- `m49_code`
- `unep_country`
- `household_food_waste_kg_capita`
- `household_food_waste_tonnes_year`
- `household_food_waste_confidence`
- `household_food_waste_source`

## `country_food_system_need_indicators_v2_analysis_ready.csv`

Columns:
- `iso3`
- `country`
- `region`
- `income_group`
- `population_year`
- `population`
- `gdp_current_usd_year`
- `gdp_current_usd`
- `rd_expenditure_pct_gdp_year`
- `rd_expenditure_pct_gdp`
- `undernourishment_pct_year`
- `undernourishment_pct`
- `child_stunting_pct_year`
- `child_stunting_pct`
- `adult_obesity_pct_year`
- `adult_obesity_pct`
- `agrifood_ghg_ktco2eq_year`
- `agrifood_ghg_ktco2eq`
- `agrifood_ghg_tco2eq_per_capita`
- `cereal_import_dependency_period`
- `cereal_import_dependency_period_end_year`
- `cereal_import_dependency_pct`
- `household_food_waste_kg_capita`
- `household_food_waste_tonnes_year`
- `household_food_waste_confidence`
- `household_food_waste_source`
- `unep_country`
- `unep_region`
- `m49_code`
- `gdp_per_capita_current_usd`
- `log10_population`
- `log10_gdp_current_usd`
- `log10_gdp_per_capita_current_usd`
- `cereal_import_dependency_vulnerability_pct`
- `need_food_security_score`
- `need_child_stunting_score`
- `need_adult_obesity_score`
- `need_nutrition_score`
- `need_food_waste_score`
- `need_sustainability_score`
- `need_supply_vulnerability_score`
- `n_need_axes_available`
- `food_system_need_index_v1`
- `household_food_waste_confidence_group`
- `food_system_need_index_v1_min3`
- `food_system_need_index_main_min4`
- `food_system_need_index_strict_all5`
- `need_social_score`
- `need_environmental_score`
- `need_resilience_score`
- `dominant_need_profile`
- `missing_need_axes`
- `flag_main_need_index_available`
- `flag_strict_need_index_available`
- `flag_population_ge_1m`
- `flag_food_waste_higher_confidence`
- `flag_food_waste_low_confidence`
- `rank_need_v1_min3`
- `rank_need_main_min4`
- `rank_need_strict_all5`
