---
title: UmbracoUserHelper
description: API reference for UmbracoUserHelper in Umbraco Commerce
---
## UmbracoUserHelper

```csharp
public class UmbracoUserHelper : IUserHelper
```

**Inheritance**

* interface [IUserHelper](../../umbraco-commerce-core/umbraco-commerce-core-security/iuserhelper.md)

**Namespace**
* [Umbraco.Commerce.Cms.Security](README.md)

### Constructors

#### UmbracoUserHelper

```csharp
public UmbracoUserHelper(IBackOfficeSecurityAccessor backOfficeSecurityAccessor, 
    IUserService userService)
```


### Methods

#### GetCurrentUserId

```csharp
public virtual int GetCurrentUserId()
```


---

#### GetUserName

```csharp
public virtual string GetUserName(int id)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.dll -->
