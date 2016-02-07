.. _class_ScrollContainer:

ScrollContainer
===============

**Inherits:** :ref:`Container<class_container>` **<** :ref:`Control<class_control>` **<** :ref:`CanvasItem<class_canvasitem>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

A helper node for displaying scrollable elements (e.g. lists).

Member Functions
----------------

+--------------------------+--------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_enable_h_scroll<class_ScrollContainer_set_enable_h_scroll>`  **(** :ref:`bool<class_bool>` enable  **)** |
+--------------------------+--------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`  | :ref:`is_h_scroll_enabled<class_ScrollContainer_is_h_scroll_enabled>`  **(** **)** const                           |
+--------------------------+--------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_enable_v_scroll<class_ScrollContainer_set_enable_v_scroll>`  **(** :ref:`bool<class_bool>` enable  **)** |
+--------------------------+--------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`  | :ref:`is_v_scroll_enabled<class_ScrollContainer_is_v_scroll_enabled>`  **(** **)** const                           |
+--------------------------+--------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_h_scroll<class_ScrollContainer_set_h_scroll>`  **(** :ref:`int<class_int>` val  **)**                    |
+--------------------------+--------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`    | :ref:`get_h_scroll<class_ScrollContainer_get_h_scroll>`  **(** **)** const                                         |
+--------------------------+--------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_v_scroll<class_ScrollContainer_set_v_scroll>`  **(** :ref:`int<class_int>` val  **)**                    |
+--------------------------+--------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`    | :ref:`get_v_scroll<class_ScrollContainer_get_v_scroll>`  **(** **)** const                                         |
+--------------------------+--------------------------------------------------------------------------------------------------------------------+

Description
-----------

A ScrollContainer node with a :ref:`Control<class_control>` child and scrollbar child (:ref:`HScrollbar<class_hscrollbar>`, :ref:`VScrollBar<class_vscrollbar>`, or both) will only draw the Control within the ScrollContainer area.  Scrollbars will automatically be drawn at the right (for vertical) or bottom (for horizontal) and will enable dragging to move the viewable Control (and its children) within the ScrollContainer.  Scrollbars will also automatically resize the grabber based on the minimum_size of the Control relative to the ScrollContainer.  Works great with a :ref:`Panel<class_panel>` control.

Member Function Description
---------------------------

.. _class_ScrollContainer_set_enable_h_scroll:

- void  **set_enable_h_scroll**  **(** :ref:`bool<class_bool>` enable  **)**

.. _class_ScrollContainer_is_h_scroll_enabled:

- :ref:`bool<class_bool>`  **is_h_scroll_enabled**  **(** **)** const

.. _class_ScrollContainer_set_enable_v_scroll:

- void  **set_enable_v_scroll**  **(** :ref:`bool<class_bool>` enable  **)**

.. _class_ScrollContainer_is_v_scroll_enabled:

- :ref:`bool<class_bool>`  **is_v_scroll_enabled**  **(** **)** const

.. _class_ScrollContainer_set_h_scroll:

- void  **set_h_scroll**  **(** :ref:`int<class_int>` val  **)**

.. _class_ScrollContainer_get_h_scroll:

- :ref:`int<class_int>`  **get_h_scroll**  **(** **)** const

.. _class_ScrollContainer_set_v_scroll:

- void  **set_v_scroll**  **(** :ref:`int<class_int>` val  **)**

.. _class_ScrollContainer_get_v_scroll:

- :ref:`int<class_int>`  **get_v_scroll**  **(** **)** const

