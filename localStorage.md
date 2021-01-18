# Local Storage

The `localStorage` and `sessionStorage` properties allow to save key/value pairs in a web browser.`localStorage` object stores data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.

**Syntax**
`window.localStorage`

**Syntax for SAVING data to localStorage:**
`localStorage.setItem("key", "value");`

**Syntax for READING data from localStorage:**
`var lastname = localStorage.getItem("key");`

**Syntax for REMOVING data from localStorage:**
`localStorage.removeItem("key");`

The read-only `localStorage` property allows you to access a Storage object for the Document's origin; the stored data is saved across browser sessions. `localStorage` is similar to `sessionStorage`, except that while data stored in `localStorage` has no expiration time, data stored in `sessionStorage` gets cleared when the page session ends — that is, when the page is closed. (Data in a `localStorage` object created in a "private browsing" or "incognito" session is cleared when the last "private" tab is closed.)
