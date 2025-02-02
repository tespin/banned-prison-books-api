## Banned Prison Books

Discover texts banned in your state's prison system.

### To Do

#### General

- documentation
- API
- integrate actions
- typescript
- random collections of banned prison texts; i.e, books banned in the last year, books banned for obscenity, books

#### Search Bar

- keep page nav fixed to stop of search bar
- aria roles
- highlighting predictive text in autocomplete
- use mm/dd/yy format for date in search results
- search by author and reason
- sort by author first and last name, most / last recent
- keys for list
- loading styles
- truncation of long descriptions
- design pass on spacing between autocomplete suggestions and search results
- keep previous search query
- focus search button when query is selected
- clear button for queries

#### Design

- color swatches
- home page desktop layout
- home page mobile layout

#### Pagination

- disabled button styling
- accessibility
- keys for each link
- disable current page button
- mobile vs desktop; infinite scrolling?
- hover styles
- page numbers look cramped when 3 digits
- if used arrow to go to 1st page or last page, focus should switch to the opposite arrow
- don't show pagination if less than one page

### use reducer refactor

- total count is wrong after activating and then deactivating a filter

#### Errors

- pressing 'enter' when there are no autocomplete suggestions for the input (whether input is nonsense or empty) results in an error
- persist filter choices when modal closes (means )
- does not remember active buttons for styling upon dialog closing
- add filtered options to results text after submitting
- clearing filter options should reset filtered data
- replicate: results not showing properly when filtering through multiple years
- new search should clear filters
