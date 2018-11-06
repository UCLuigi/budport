# budport
An ERP system for dispensaries

[Pivotal Tracker](https://www.pivotaltracker.com/n/projects/2223342)


Backend
- crud for inventory
    - create
    - read
    - update
    - delete
- inventory
    - categories
    - items
    - tags (recommendation system based on tags possibly)
        - look at leafly for ideas
    - images
- customer management
    - update customers
    - create customers
        - id
        - image
        - name
        - dob
        - pre-selected preferences
    - add/delete items to customers (cart)
    - reviews for items from customer
    - possible recommendations
    - history
    - promotions
    - customer can checkout various dispensaries visited before
- QR code

## Use Case
1. QR code scans then identifies them when they first enter dispensary
2. This will then go to bud tenders systems and notifies them with all ur info
3. Bud tenders put customers orders in systems which creates a history for the customer for later recommendations (they can ask customers how they liked previous orders)
4. Could even try to make bud tenders salesmen by giving commission depending on if customer is a big spender and made them spend more


selling platform/data to dispensaries for customer information to better appeal and attract customers through personalization
