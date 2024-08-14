# Solutions to the bugs
### Bug 1
- Edited the `index.css` file. 
- removed the `position:fixed` at `RampInputSelect--dropdown-container` class.
- Bug Fixed

### Bug 2
- Edited the `inputCheckBox/index.tsx` file.
- added `onclick={document.getElementById(inputId).click()}` to a label with class `RampInputCheckbox--label`
- Bug Fixed

### BUg 3
- Edited the `App.tsx` file
- Added `if (newValue.id === ""){
            return loadAllTransactions()
         }` to `Onchange()` function in `InputSelect` to check for empty employee `id`
- Bug Fixed

### Bug 4
- edited the `usePaginatedTransactions.ts` file.
- added `previousResponse.data.concat(reponse.data)` in `setPaginatedTransactions` method.
- Bug Fixed

### Bug 5
- edited `fetch.ts` file.
- edited the values from `1.5` and `2.5` to `0.5`.
- Now appears to disappear as soon as output appears on console

### Bug 6
- edited the `App.tsx` file.
- edited the line from `{transactions !== null &&(` to ` {paginatedTransactions?.nextPage && transactions !== null && transactionsByEmployee == null ?`
- Bug Fixed
