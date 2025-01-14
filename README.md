# React Tabs with Router
- [DEMO LINK](https://YegorKochetkov.github.io/react_tabs-with-router/)

## Description
Implement an App with a navigation and 2 pages:

1. Show `<h1>Home page</h1>` on `http://localhost:3000`.
1. Show `TabsPage` component on `http://localhost:3000/#/tabs`. Use these tabs:
    ```javascript
    let tabs = [
      { id: 'tab-1', title: 'Tab 1', content: 'Some text 1' },
      { id: 'tab-2', title: 'Tab 2', content: 'Some text 2' },
      { id: 'tab-3', title: 'Tab 3', content: 'Some text 3' },
    ];
    ```
1. Add a navigation to `Home` or `Tabs` page
    - The navigation should be visible everywhere.
    - An active link should be highlighted.
1. `TabsPage` should show a list of tabs.
    - When you select a tab the URL should be changed to `/tabs/tab-1` (use actual `tab.id`).
    - a tab content should be shown below the list
    - the selected tab should be highlighted by changing the class of the `<a>` element.
1. After the page reload you should see a content of the tab matching the `id` from the URL.
    - If the `id` is not valid or is not set (e.g just `/tabs`) show `Please select a tab` message.

![tabs](./description/tabs.gif)
