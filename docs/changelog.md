# Changelog

This section contains changes that are specific to the requirements for achieving UK compliance. For a list of changes to the broader HSDS standard, please see the [Changelog](https://docs.openreferral.org/en/latest/hsds/changelog.html) page.

## v3.0

### Services

#### Added

* `alert`
* `alternate_name`
* `application_process`
* `assurer_email`
* `attributes` (collection)
* `metadata` (collection)
* `eligibility_description`
* `fees_description`
* `interpretation_services`
* `last_modified`
* `licenses`
* `maximum_age`
* `metadata`
* `minimum_age`
* `wait_time`


#### Removed

* `deliverable_type`
* `eligibilitys` (collection)
* `holiday_schedules` (collection)
* `reviews` (collection)
* `service_taxonomys` (collection)

#### Renamed

* `fundings to funding` (collection)
* `regular_schedules to schedules` (collection)

### Phones

#### Replaced

* `contact` replaced with `description`

#### Added

* `extension`
* `languages`
* `metadata`
* `type`

### Contacts

#### Added

* `attributes` (collection)
    * `phones`
    * `program`
    * `required_documents`


#### Removed

* `service`

### cost_options

#### Added

* `attributes`
* `metadata`
* `currency`

#### Removed

* `linkId`
* `service`

### language

#### Added

* `attributes`
* `code`
* `name`
* `metadata`
* `note`

#### Removed

* `language`
* `serviceId`

### organization

#### Added

* `alternate_name`
* `attributes`
* `contacts`
* `email`
* `funding`
* `legal_status`
* `locations`
* `metadata`
* `organization_identifiers`
* `parent_organization_id`
* `phones`
* `programs`
* `tax_id`
* `tax_status`
* `website`
* `year_incorporated`

### service_areas

#### Added

* `attributes`
* `description`
* `extent_type`
* `metadata`
* `name`

### service_at_locations

#### Added

* `attributes`
* `contacts`
* `description`
* `location`

### location

#### Added

* `accessibility`
* `addresses`
* `alternate_name`
* `attributes`
* `contacts`
* `external_identifier`
* `external_identifier_type`
* `languages`
* `location_type`
* `metadata`
* `phones`
* `schedules`
* `transportation`
* `url`
