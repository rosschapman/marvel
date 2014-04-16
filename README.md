marvel
======

### PROJECT PLAN

**OG Pseudo-code summary:**
User inputs 2 characters.
User clicks button.
     Must validate for minimum of 2 characters.
Make GET API call to Marvel.
Build dates array: data.results[x].dates[0].date
Feed new dates array into D3 chart

**Tasks:**
* Figure out data model
* Parse data stub
* Character Form
  * Two input fields
  * Search by name? / A-Z? / video game vs selection?
    * Search: Fields have autocomplete
  * Show character after select
  * Should probably be multi-step, add one character then the next

**Milestones:**
* Build form that accepts 2 characters by name and retrieves data from Marvel API
* Plot data on a timeline
* Hookup form submission to graph plot
* Implement an awesome design/interface