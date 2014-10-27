## Rangle IO Angualr JS Session

# Oct 27 2014

1.  History of JS

Java and JS may look similar, but not really.

2.  Angular 

Framework that has been meticulously thought out an engineered (by Google!).  However, many pitfalls.

Like JS: find the good parts, stick to them. 

3.  MVVM

"controllers" - set up a specific data structure ($scope), let the view layer (Angular) perform the manipulation. 

"services" - model (data and biz logic).  Building services (our model) is where we should spend most of our time. 

**Angular 80/20: Model/View**

Why? Services are **easy to test**!  They are the "low-hanging fruit".

Angular gives you the opportunity for views to talk to various VMs, which talk to various Models.  VMs don't talk to each other.  Rely on communication in the deeper layer, aka services, not on the VM (or controller level).

Service layer has no reference to the current view.  Controllers (VM) will interface with the views (thus controlling the state for the user).

# Outline

Controllers 

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```











