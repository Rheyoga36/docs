---
ms.openlocfilehash: de2ab71ca5c93229329c2887dc71685aa92e199d
ms.sourcegitcommit: fcf3546b7cc208155fb8acdf68b81be28afc3d2d
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/10/2022
ms.locfileid: "145069555"
---
Puedes especificar eventos sencillos o múltiples. Por ejemplo, un flujo de trabajo con el siguiente valor de `on` se ejecutará cuando se realice una inserción en cualquier rama del repositorio o cuando alguien lo bifurque:

```yaml
on: [push, fork]
```

Si especificas eventos múltiples, únicamente uno de ellos necesitará ocurrir para que se active tu flujo de trabajo. Si ocurren eventos múltiples de activación para tu flujo de trabajo al mismo tiempo, se activarán las ejecuciones de flujo de trabajo múltiples.
