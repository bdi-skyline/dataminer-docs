---
uid: Adding_an_item_to_a_dashboard_from_outside_the_Dashboards_app
---

# Adding an item to a dashboard from outside the Dashboards app

From DataMiner 9.0 onwards, it is possible to add items to a dashboard directly from the Cube UI, for instance from the Surveyor or an element card.

1. Select the *Add to dashboard* option in one of the following menus:

    - The context menu of a parameter, for instance on an element card.

    - The context menu of an element or service, for instance in the Surveyor.

    - The header bar menu of an element or service card.

    - The context menu of a trend graph.

    - The context menu of a table on a Data Display page of a card.

2. Select whether to add the item to a *New dashboard* or an *Existing dashboard*.

    If you select *Existing dashboard*, a short list of dashboards will be displayed. Select *Show all* if the dashboard you need is not yet included in the list.

3. If you are adding an element or service, select the type of component you want to add:

    - **Alarm count**: Adds an *Alarm Count* component. See [Alarm count element](xref:Dashboard_components#alarm-count-element) or [Alarm count service](xref:Dashboard_components#alarm-count-service).

    - **Alarm state**: Adds an *Alarm State* component. See [Alarm state element](xref:Dashboard_components#alarm-state-element) or [Alarm state service](xref:Dashboard_components#alarm-state-service).

    - **Visio**: Adds a *Visual Overview* component. See [Visual overview element](xref:Dashboard_components#visual-overview-element) or[Visual overview service](xref:Dashboard_components#visual-overview-service).

    - **Element LED**: Adds an *Element State LED* component. See [Element state LED](xref:Dashboard_components#element-state-led).

    - **All LEDs**: Adds a *Parameter State LED* component for every parameter in the selected service or element. See [Parameter state LED](xref:Dashboard_components#parameter-state-led).

    > [!NOTE]
    > - If you are adding a parameter, a table cell or a table row, the added component will always be a generic real-time parameter component.
    > - If you are adding a trend graph, the added component will always be a trend parameter component.

4. Either click *Add* to simply add the item to the dashboard, or click *Add and show* to also immediately open the dashboard in a different tab of your browser.
