---
title: 'Explicador: o que é uma assinatura do Azure?'
description: Explica as assinaturas, contas e ofertas do Azure
author: alexbuckgit
ms.openlocfilehash: 1650d90d6f78b46b7fe4128d2dab6a80bd6cca78
ms.sourcegitcommit: 3d9ee03e2dda23753661a80c7106d1789f5223bb
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 02/23/2018
ms.locfileid: "29478299"
---
# <a name="explainer-what-is-an-azure-subscription"></a>Explicador: o que é uma assinatura do Azure?

No artigo do explicador [O que é um locatário do Azure Active Directory?](tenant-explainer.md), você aprendeu que a identidade digital de sua organização é armazenada em um locatário do Azure Active Directory. Você também aprendeu que o Azure confia no Azure Active Directory para autenticar solicitações do usuário para criar, ler, atualizar ou excluir um recurso. 

Compreendemos a essência da necessidade de restringir o acesso a essas operações em um recurso – impedir que usuários não autenticados e não autorizados acessem nossos recursos. No entanto, essas operações de recurso têm outras propriedades que uma organização deseja controlar, como o número de recursos que um usuário ou grupo de usuários tem permissão para criar e o custo de execução desses recursos. 

O Azure implementa esse controle e ele é chamado de uma **assinatura**. Uma assinatura agrupa usuários e os recursos que foram criados pelos usuários. Cada um desses recursos contribui para um [limite geral][subscription-service-limits] nesse recurso específico.

As organizações podem usar assinaturas para gerenciar os custos e a criação de recursos por usuários, equipes, projetos ou usando muitas outras estratégias. Essas estratégias serão discutidas nos artigos sobre os estágios intermediário e avançado de adoção. 

## <a name="next-steps"></a>Próximas etapas

* Agora que você aprendeu sobre as assinaturas do Azure, saiba mais sobre [como criar uma assinatura](subscription.md) antes de criar seus primeiros recursos do Azure.

<!-- Links -->
[azure-get-started]: https://azure.microsoft.com/get-started/
[azure-offers]: https://azure.microsoft.com/support/legal/offer-details/
[azure-free-trial]: https://azure.microsoft.com/offers/ms-azr-0044p/
[azure-change-subscription-offer]: /azure/billing/billing-how-to-switch-azure-offer
[microsoft-account]: https://account.microsoft.com/account
[subscription-service-limits]: /azure/azure-subscription-service-limits
[docs-organizational-account]: https://docs.microsoft.com/azure/active-directory/sign-up-organization
