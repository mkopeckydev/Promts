Do třídy EmailTemplate přibylo nové pole PaymentType, doplň mi toto pole do datové fasády s názvem EmailTemplateFacade, podobně jako ostatní pole

##

Uprav komponentu ucSettingsEmailTemplates.ascx, přidej mi tam nové pole PaymentType s popiskem Typ platby, toto pole umísti za pole Dopravce. Pole má max délku 256, doplň v kódu všechny odpovídající operace

##

Do třídy EmailTemplate přidej novu funkci CheckFilterPaymentType, která bude fungovat stejně jako již existující CheckFilterCarrier, ale bude pracovat s polem PaymentType. Nově přidanou funkci pak přidej k použití v datové fasádě EmailTemplateFacade.

##

Do třídy NumberMapping přibylo nové pole ClassificationVAT, doplň mi toto pole do datové fasády s názvem NumberMappingFacade, podobně jako ostatní pole
Uprav komponentu ucSettingsNumberMapping.ascx, přidej mi tam nové pole ClassificationVAT s popiskem Členění DPH, toto pole umísti za pole Předkontace. Pole se bdue editovat komponentou UC:Select, pro načtení položek použit metodu PohodaFacade.GetClassificationVAT

##