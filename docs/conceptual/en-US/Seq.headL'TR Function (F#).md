# Seq.head<'T> Function (F#)

Returns the first element of the sequence.

**Namespace/Module Path**: Microsoft.FSharp.Collections.Seq

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD

```
// Signature:
Seq.head : seq<'T> -> 'T

// Usage:
Seq.head source
```

#### CAPS_PARAMETERS_MD
*source*
Type: [seq](http://msdn.microsoft.com/en-us/library/2f0c87c6-8a0d-4d33-92a6-10d1d037ce75)**&lt;'T&gt;**


The input sequence.



**exceptions tag is not supported!!!!**
**The first element of the sequence.**
## CAPS_REMARKS_MD
The first element of the *source* sequence is evaluated at each call. To avoid this reevaluation, you can create a cached version of a sequence by calling [Seq.cache](http://msdn.microsoft.com/en-us/library/d197f9cc-08bf-4986-9869-246e72ca73f0).

This function is named **Head** in compiled assemblies. If you are accessing the function from a language other than F#, or through reflection, use this name.

**The following code shows how to use Seq.head.**
```

    let headItem = Seq.head [| 1 .. 10 |]
    printfn "%d" headItem
```

**Output**
**1**
## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Collections.Seq Module &#40;F&#35;&#41;](Collections.Seq+Module+%28F%23%29.md)

[Microsoft.FSharp.Collections Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Collections+Namespace+%28F%23%29.md)
