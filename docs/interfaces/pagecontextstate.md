[@ballware/react-contexts](../README.md) / [Exports](../modules.md) / PageContextState

# Interface: PageContextState

Context for page layout functionality

## Hierarchy

* **PageContextState**

## Table of contents

### Properties

- [customParam](pagecontextstate.md#customparam)
- [documentation](pagecontextstate.md#documentation)
- [layout](pagecontextstate.md#layout)
- [loadDocumentation](pagecontextstate.md#loaddocumentation)
- [pageParam](pagecontextstate.md#pageparam)
- [paramEditorEvent](pagecontextstate.md#parameditorevent)
- [paramEditorInitialized](pagecontextstate.md#parameditorinitialized)
- [paramEditorValueChanged](pagecontextstate.md#parameditorvaluechanged)
- [paramsInitialized](pagecontextstate.md#paramsinitialized)
- [resetDocumentation](pagecontextstate.md#resetdocumentation)

## Properties

### customParam

• `Optional` **customParam**: *undefined* \| *Record*<*string*, *unknown*\>

Custom param provided by custom page scripts

Defined in: [src/pagecontext.ts:33](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L33)

___

### documentation

• `Optional` **documentation**: *undefined* \| *string*

Documentation text provided for display

Defined in: [src/pagecontext.ts:38](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L38)

___

### layout

• `Optional` **layout**: *undefined* \| PageLayout

Current provided page layout

Defined in: [src/pagecontext.ts:23](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L23)

___

### loadDocumentation

• `Optional` **loadDocumentation**: *undefined* \| (`identifier`: *string*) => *void*

Load documentation for documentation identifier

Defined in: [src/pagecontext.ts:43](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L43)

___

### pageParam

• `Optional` **pageParam**: *undefined* \| *Record*<*string*, *string* \| *number* \| *boolean* \| (*string* \| *number* \| *boolean*)[]\>

Page param provided by param editors or url

Defined in: [src/pagecontext.ts:28](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L28)

___

### paramEditorEvent

• `Optional` **paramEditorEvent**: *undefined* \| (`name`: *string*, `event`: *string*, `editUtil`: EditUtil, `param?`: ValueType) => *void*

Parameter editor event triggered

**`param`** Identifier of parameter editor

**`param`** Specific identifier of event

**`param`** Adapter for access to parameter editor instances

**`param`** Optional event specific parameter

Defined in: [src/pagecontext.ts:82](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L82)

___

### paramEditorInitialized

• `Optional` **paramEditorInitialized**: *undefined* \| (`identifier`: *string*, `editUtil`: EditUtil) => *void*

Parameter editor for identifier is inizialized (and displayed)

**`param`** Identifier of parameter editor

**`param`** Adaptor for access to parameter editor instances

Defined in: [src/pagecontext.ts:61](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L61)

___

### paramEditorValueChanged

• `Optional` **paramEditorValueChanged**: *undefined* \| (`name`: *string*, `value`: ValueType, `editUtil`: EditUtil) => *void*

Parameter editor value changed

**`param`** Identifier of parameter editor

**`param`** Current value of parameter editor

**`param`** Adapter for access to parameter editor instances

Defined in: [src/pagecontext.ts:69](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L69)

___

### paramsInitialized

• `Optional` **paramsInitialized**: *undefined* \| (`hidden`: *boolean*) => *void*

All parameter editors initialized

**`param`** True if parameter editor display is hidden because of media limitations

Defined in: [src/pagecontext.ts:54](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L54)

___

### resetDocumentation

• `Optional` **resetDocumentation**: *undefined* \| () => *void*

Hide documentation for display

Defined in: [src/pagecontext.ts:48](https://github.com/frankball/ballware-react-contexts/blob/34223fb/src/pagecontext.ts#L48)
