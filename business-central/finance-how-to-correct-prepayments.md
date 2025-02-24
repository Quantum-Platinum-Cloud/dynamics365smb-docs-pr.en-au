---
title: Correct Prepayments
description: You can make a correction to an order after you have posted a prepayment invoice for the order and add new lines to an order after issuing a prepayment.
author: SorenGP
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.form: '44, 48, 42, 50, 52, 9305, 9307'
ms.date: 06/16/2021
ms.author: edupont
---
# <a name="correct-prepayments" />Correct Prepayments

You can make a correction to an order after you have posted a prepayment invoice for the order. You can add new lines to an order after issuing a prepayment, and then you can post another prepayment invoice, but you cannot delete a line from an order after a prepayment has been invoiced for the line.  

> [!TIP]
> If you have posted a prepayment invoice for a sales invoice that you then correct or cancel, you must correct or cancel the prepayment as well.

## <a name="to-correct-a-prepayment" />To correct a prepayment

The following procedure shows how to issue a prepayment CR/Adj note to cancel all invoiced prepayments for a sales order.  

1. Choose the ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Sales Orders**, and then choose the related link.  
2. Open the relevant sales order.
3. Choose the **Prepayment** action, and then choose the **Post Prepayment Credit Adjustment Note** action or the **Post and Print Prepmt. CR/Adj Note. Memo** action.  
4. On the **Sales CR/Adj Note** page, proceed to correct the relevant entries, as for any sales CR/Adj Note. For more information, see [Process Sales Returns or Cancellations](sales-how-process-sales-returns-cancellations.md).  

    > [!NOTE]  
    > To reduce the amount in the **Line Amount** field, you must first increase the prepayment percentage on the line so that the value in the **Prepmt. Line Amount** field is not decreased below the value in the **Prepmt. Amt. Inv.** field.

5. To make a prepayment invoice for any new lines in the sales CR/Adj note, choose the **Prepayment** action, and then choose the **Post Prepayment Invoice** action or the **Post and Print Prepmt. Invoice** action.  
6. To issue an additional prepayment invoice, increase the prepayment amount on one or more lines and post the prepayment invoice. A new invoice will be created for the difference between the prepayment amounts invoiced and the new prepayment amounts.  

## <a name="see-related-microsoft-trainingtrainingmodulesprepayment-invoices-dynamics-365-business-central" />See related [Microsoft training](/training/modules/prepayment-invoices-dynamics-365-business-central/)

## <a name="see-also" />See also

[Invoicing Prepayments](finance-invoice-prepayments.md)  
[Walkthrough: Setting Up and Invoicing Sales Prepayments](walkthrough-setting-up-and-invoicing-sales-prepayments.md)  
[Finance](finance.md)  
[Work with [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)  


[!INCLUDE[footer-include](includes/footer-banner.md)]
