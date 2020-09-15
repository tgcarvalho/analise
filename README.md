# EHR Linked Data

EHR Linked Data is a specific component for rendering ehr linked data attributes.

- [Events](#Events)
- [Methods](#Methods)

## Events

- [onLoad](#onLoad)
- [onDestroy](#onDestroy)


### onLoad

---

#### :clock230: When?

This event fired after the component be load

#### :bookmark_tabs: Parameters

**handler:** _(Object)_ EHR Linked Data Component handler <br>

#### :pencil2: Example

```html
<w-ehr-linked-data
 w-onLoad="onLoad($handler)">

</w-ehr-linked-data>
```

```javascript
const onLoad = (handler) => {
  handler.exampleHandlerMethod();
};
```


### onDestroy

---

#### :clock230: When?

This event fired after the component be destroyed

#### :bookmark_tabs: Parameters

**handler:** _(Object)_ EHR Linked Data Component handler <br>

#### :pencil2: Example

```javascript
const onLoad = (handler) => {
  handler.events.onDestroy.addListener(() => doSomething());
};
```
=======

## Methods

- [exampleHandlerMethod](#exampleHandlerMethod)


### exampleHandlerMethod

---

#### :page_with_curl: Description

example description

#### :bookmark_tabs: Parameters

Not available

#### :leftwards_arrow_with_hook: Return

Not available

#### :pencil2: Example

```javascript
// example code
```
