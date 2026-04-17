# Form Functional Test — Cypress Automation

---

## Objective

Evaluate the functionality of form submission using automated testing, ensuring that the system correctly processes user input and displays the expected result.

---

## Test Scope

The test focused on the following functionalities:

- Email input field interaction
- Form submission process
- Validation of success message display

---

## Test Environment

- Tested System: Cypress Kitchen Sink
- Device: Desktop / Notebook
- Operating System: Windows 10
- Browser: Microsoft Edge
- Test Type: Automated Functional Test

---

## Test Cases Executed

ID| Scenario| Expected Result| Status
TC-001| Enter valid email and submit form| Success message should be displayed| Passed

---

## Automation Code

describe('Form Test', () => {
  it('should fill form and submit', () => {
    cy.visit('https://example.cypress.io/commands/actions')

    cy.get('.action-email').type('test@email.com')
    cy.get('.action-form').submit()

    cy.contains('Your form has been submitted!').should('be.visible')
  })
})

---

## Conclusion

The automated test confirmed that the form submission functionality is working as expected. The system correctly handles user input and displays the appropriate success message.
