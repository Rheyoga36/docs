---
ms.openlocfilehash: 00bdf100d02b27ce76aff35582cb4a1f5a2469a3
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/05/2022
ms.locfileid: "145095042"
---
1. Configure um perfil de publicação do Azure e crie um segredo `AZURE_WEBAPP_PUBLISH_PROFILE`.

   Gere suas credenciais de implantação do Azure usando um perfil de publicação. Para obter mais informações, confira "[Gerar credenciais de implantação](https://docs.microsoft.com/azure/app-service/deploy-github-actions?tabs=applevel#generate-deployment-credentials)" na documentação do Azure.

   No repositório do {% data variables.product.prodname_dotcom %}, crie um segredo chamado `AZURE_WEBAPP_PUBLISH_PROFILE` que inclua o conteúdo do perfil de publicação. Para obter mais informações sobre como criar segredos, confira "[Segredos criptografados](/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-a-repository)".
