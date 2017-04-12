.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the doc/base/classes.xml source instead.

.. _class_AudioEffectChorus:

AudioEffectChorus
=================

**Inherits:** :ref:`AudioEffect<class_audioeffect>` **<** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------



Member Functions
----------------

+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_dry<class_AudioEffectChorus_get_dry>`  **(** **)** const                                                                                         |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`      | :ref:`get_voice_count<class_AudioEffectChorus_get_voice_count>`  **(** **)** const                                                                         |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_voice_cutoff_hz<class_AudioEffectChorus_get_voice_cutoff_hz>`  **(** :ref:`int<class_int>` voice_idx  **)** const                                |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_voice_delay_ms<class_AudioEffectChorus_get_voice_delay_ms>`  **(** :ref:`int<class_int>` voice_idx  **)** const                                  |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_voice_depth_ms<class_AudioEffectChorus_get_voice_depth_ms>`  **(** :ref:`int<class_int>` voice_idx  **)** const                                  |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_voice_level_db<class_AudioEffectChorus_get_voice_level_db>`  **(** :ref:`int<class_int>` voice_idx  **)** const                                  |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_voice_pan<class_AudioEffectChorus_get_voice_pan>`  **(** :ref:`int<class_int>` voice_idx  **)** const                                            |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_voice_rate_hz<class_AudioEffectChorus_get_voice_rate_hz>`  **(** :ref:`int<class_int>` voice_idx  **)** const                                    |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`  | :ref:`get_wet<class_AudioEffectChorus_get_wet>`  **(** **)** const                                                                                         |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_dry<class_AudioEffectChorus_set_dry>`  **(** :ref:`float<class_float>` amount  **)**                                                             |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_voice_count<class_AudioEffectChorus_set_voice_count>`  **(** :ref:`int<class_int>` voices  **)**                                                 |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_voice_cutoff_hz<class_AudioEffectChorus_set_voice_cutoff_hz>`  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` cutoff_hz  **)** |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_voice_delay_ms<class_AudioEffectChorus_set_voice_delay_ms>`  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` delay_ms  **)**    |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_voice_depth_ms<class_AudioEffectChorus_set_voice_depth_ms>`  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` depth_ms  **)**    |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_voice_level_db<class_AudioEffectChorus_set_voice_level_db>`  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` level_db  **)**    |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_voice_pan<class_AudioEffectChorus_set_voice_pan>`  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` pan  **)**                   |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_voice_rate_hz<class_AudioEffectChorus_set_voice_rate_hz>`  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` rate_hz  **)**       |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                       | :ref:`set_wet<class_AudioEffectChorus_set_wet>`  **(** :ref:`float<class_float>` amount  **)**                                                             |
+----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

- :ref:`float<class_float>` **dry**
- :ref:`float<class_float>` **voice/1/cutoff_hz**
- :ref:`float<class_float>` **voice/1/delay_ms**
- :ref:`float<class_float>` **voice/1/depth_ms**
- :ref:`float<class_float>` **voice/1/level_db**
- :ref:`float<class_float>` **voice/1/pan**
- :ref:`float<class_float>` **voice/1/rate_hz**
- :ref:`float<class_float>` **voice/2/cutoff_hz**
- :ref:`float<class_float>` **voice/2/delay_ms**
- :ref:`float<class_float>` **voice/2/depth_ms**
- :ref:`float<class_float>` **voice/2/level_db**
- :ref:`float<class_float>` **voice/2/pan**
- :ref:`float<class_float>` **voice/2/rate_hz**
- :ref:`float<class_float>` **voice/3/cutoff_hz**
- :ref:`float<class_float>` **voice/3/delay_ms**
- :ref:`float<class_float>` **voice/3/depth_ms**
- :ref:`float<class_float>` **voice/3/level_db**
- :ref:`float<class_float>` **voice/3/pan**
- :ref:`float<class_float>` **voice/3/rate_hz**
- :ref:`float<class_float>` **voice/4/cutoff_hz**
- :ref:`float<class_float>` **voice/4/delay_ms**
- :ref:`float<class_float>` **voice/4/depth_ms**
- :ref:`float<class_float>` **voice/4/level_db**
- :ref:`float<class_float>` **voice/4/pan**
- :ref:`float<class_float>` **voice/4/rate_hz**
- :ref:`int<class_int>` **voice_count**
- :ref:`float<class_float>` **wet**

Member Function Description
---------------------------

.. _class_AudioEffectChorus_get_dry:

- :ref:`float<class_float>`  **get_dry**  **(** **)** const

.. _class_AudioEffectChorus_get_voice_count:

- :ref:`int<class_int>`  **get_voice_count**  **(** **)** const

.. _class_AudioEffectChorus_get_voice_cutoff_hz:

- :ref:`float<class_float>`  **get_voice_cutoff_hz**  **(** :ref:`int<class_int>` voice_idx  **)** const

.. _class_AudioEffectChorus_get_voice_delay_ms:

- :ref:`float<class_float>`  **get_voice_delay_ms**  **(** :ref:`int<class_int>` voice_idx  **)** const

.. _class_AudioEffectChorus_get_voice_depth_ms:

- :ref:`float<class_float>`  **get_voice_depth_ms**  **(** :ref:`int<class_int>` voice_idx  **)** const

.. _class_AudioEffectChorus_get_voice_level_db:

- :ref:`float<class_float>`  **get_voice_level_db**  **(** :ref:`int<class_int>` voice_idx  **)** const

.. _class_AudioEffectChorus_get_voice_pan:

- :ref:`float<class_float>`  **get_voice_pan**  **(** :ref:`int<class_int>` voice_idx  **)** const

.. _class_AudioEffectChorus_get_voice_rate_hz:

- :ref:`float<class_float>`  **get_voice_rate_hz**  **(** :ref:`int<class_int>` voice_idx  **)** const

.. _class_AudioEffectChorus_get_wet:

- :ref:`float<class_float>`  **get_wet**  **(** **)** const

.. _class_AudioEffectChorus_set_dry:

- void  **set_dry**  **(** :ref:`float<class_float>` amount  **)**

.. _class_AudioEffectChorus_set_voice_count:

- void  **set_voice_count**  **(** :ref:`int<class_int>` voices  **)**

.. _class_AudioEffectChorus_set_voice_cutoff_hz:

- void  **set_voice_cutoff_hz**  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` cutoff_hz  **)**

.. _class_AudioEffectChorus_set_voice_delay_ms:

- void  **set_voice_delay_ms**  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` delay_ms  **)**

.. _class_AudioEffectChorus_set_voice_depth_ms:

- void  **set_voice_depth_ms**  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` depth_ms  **)**

.. _class_AudioEffectChorus_set_voice_level_db:

- void  **set_voice_level_db**  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` level_db  **)**

.. _class_AudioEffectChorus_set_voice_pan:

- void  **set_voice_pan**  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` pan  **)**

.. _class_AudioEffectChorus_set_voice_rate_hz:

- void  **set_voice_rate_hz**  **(** :ref:`int<class_int>` voice_idx, :ref:`float<class_float>` rate_hz  **)**

.. _class_AudioEffectChorus_set_wet:

- void  **set_wet**  **(** :ref:`float<class_float>` amount  **)**

