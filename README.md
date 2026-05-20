Esha Shah  

1. Within a Github Action that runs whenever code is pushed because the point of automating the tests is so that they can be run continously duing the Recipe pipeline's development to catch errors while incrementing, instead of letting them accumulate at the end.  
2. No, because E2E tests are meant to test the application from a user's point of view, primarily going through the motions of the frontend components.  
3. Navigation mode tests the page right after it's been re-loaded, Snapshot mode tests the page in it's current state.  
4. The speed index can be improved (2.2s might be too long for a webpage to load) by caching and re-routing network requests, have the page specify a lang attribute for <html> element, add meta description tag 



