# -symfony
index key
*@ORM\Table(name="customer_vehicles",indexes={@ORM\Index(name="index_customer_id", columns={"customer_id"})})


cache clear
   php bin/console cache:clear --no-warmup -e prod
   
entity comment
* @ORM\Column(name="pcc_submitted", type="integer", options={"comment":"0 for no, 1 for yes"})

To generate controller
php bin/console generate:controller

for create a table
php bin/console generate:doctrine:entity

to create a new column to table
php bin/console doctrine:generate:entities

to show table in database
php bin/console doctrine:schema:update --dump-sql
php bin/console doctrine:schema:update --force
