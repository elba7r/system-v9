A Item Variant is a version of a Item, such as differing sizes or differing colours (like a _blue_ t-shirt in size _small_ rather then just a t-shirt).
Without Item variants, you would have to treat the _small, medium_ and _large_ versions of a t-shirt as three separate Items; 
Item variants let you treat the _small, medium_ and _large_ versions of a t-shirt as variations of the one Item 't-shirt'.

To use Item Variants in Revalue ERP, create an Item and check 'Has Variants'.

* The Item shall then be referred to as a so called 'Template'. Such a Template is not identical to a regular 'Item' any longer. For example it (the Template) can not be used directly in any Transactions (Sales Order, Delivery Note, Purchase Invoice) itself. Only the Variants of an Item (_blue_ t-shirt in size _small)_ can be practically used in such. Therefore it would be ideal to decide whether an item 'Has Variants' or not directly when creating it. 

<img class="screenshot" alt="Has Variants" src="{{docs_base_url}}/assets/img/stock/item-has-variants.png">

On selecting 'Has Variants' a table shall appear. Specify the variant attributes for the Item in the table.
In case the attribute has Numeric Values, you can specify the range and increment values here. 

<img class="screenshot" alt="Valid Attributes" src="{{docs_base_url}}/assets/img/stock/item-attributes.png">

> Note: You cannot make Transactions against a 'Template'

To create 'Item Variants' against a 'Template' select 'Make Variants'

<img class="screenshot" alt="Make Variants" src="{{docs_base_url}}/assets/img/stock/make-variant.png">

<img class="screenshot" alt="Make Variants" src="{{docs_base_url}}/assets/img/stock/make-variant-1.png">

To learn more about setting Attributes Master check [Item Attributes]({{docs_base_url}}/user/manual/en/stock/setup/item-attribute.html)
