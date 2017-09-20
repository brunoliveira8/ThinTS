[thints](../README.md) > [DELETE](../interfaces/delete.md)



# Interface: DELETE

*__external__*: ThRouter DELETE

*__whatitdoes__*: Delete Decorator

     @ThRouter('/my')
    class MyRouter {
     @DELETE('/all')
     getAll(req: Request, res: Response) {
       res.json({all: []})
     }
    }

or

     @ThRouter('/my')
    class MyRouter {
     @DELETE()
     all(req: Request, res: Response) {
       res.json({all: []})
     }
    }

*__description__*: Used to inform http method and path in router. If you not pass the path name, router name will be used.

*__stable__*: 



## Properties
<a id="path"></a>

### «Optional» path

**●  path**:  *`undefined`⎮`string`* 

*Defined in [metadata.ts:580](https://github.com/murilopl/ThinTS/blob/master/src/metadata.ts#L580)*





___

