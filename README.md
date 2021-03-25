# Reproduction for a Meteor caching related bug

This app demonstrates how Meteor uses code that was cached in dev mode to build a production build.

### How to

1. clone
2. npm install
3. meteor
4. observe how there is an dev-only complaint in the browser console due to a Svelte component receiving an unused prop
4. ctrl+c
5. meteor --production
6. observe how the dev-only complaint is still present
7. ctrl+c
8. meteor reset
9. meteor --production
10. the complaint is now gone

