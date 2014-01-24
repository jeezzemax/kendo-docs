---
title: kendo.diagram.connector
meta_title: API Reference for methods, objects and properties in the Connector - diagram's primitive
meta_description: Examples and detailed explanation of Kendo UI methods and properties.
slug: api-framework
tags: api,framework
publish: false
---

# kendo.diagram.connector

The Connector object is a visual intermediate between the Connection and the Shape, it represents the attachment point of a Connection to a Shape.

## Configuration

### width `Number` *(default: 8)*

Defines the width of the connector.

### height `Number` *(default: 8)*

Defines the height of the connector.

### background `String` *(default: "Yellow")*

Defines the background color of the Connector. The Connector visual is by default an SVG Ellipse and all connectors are children of the same SVG Group. This background color is the SVG fill attribute of the Ellipse.

### hoveredBackground `String` *(default: "#70CAFF")*

Defines the color of the Connector when the pointer hovers over it.

### cssClass `String` *(default: "k-connector")*

Defines the CSS class of the SVG visual representing the Connector.

### position

Returns the position in global coordinates of the Connector.
