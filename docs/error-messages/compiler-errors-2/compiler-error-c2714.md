---
title: "Compiler Error C2714"
ms.date: "11/04/2016"
f1_keywords: ["C2714"]
helpviewer_keywords: ["C2714"]
ms.assetid: 401a5a42-660c-4bad-9d63-1a2d092bc489
---
# Compiler Error C2714

__alignof(void) is not allowed

An invalid value was passed to an operator.

See [__alignof Operator](../../cpp/alignof-operator.md) for more information.

## Example

The following sample generates C2714.

```
// C2714.cpp
int main() {
   return __alignof(void);   // C2714
   return __alignof(char);   // OK
}
```