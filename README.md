# Composable React Pages - CORP

Provides a framework for implementing a page / site builder tool with React components.

Main entities:

Page - has regions

Regions - are invisible - they are placeholders for components specified on Page Instances


```
+------------------------------------+
|                                    |
|  Page Entity - Type: Page1 +---------------------------->   Page1.jsx
|                                    |
|   +--------------------------+     |
|   |Region: Body              |     |
|   |                          |     |
|   |                          |     |
|   |                          |     |
|   +--------------------------+     |
|                                    |
|   +--------------------------+     |
|   |Region: Footer            |     |
|   |                          |     |
|   +--------------------------+     |
|                                    |
+------------------------------------+

```
