# mongoDB
The preeminent document database globally has transformed into the most adaptable developer data platform worldwide.


In this directory, I'll attempt to begin learning MongoDB

## Installing MongoDB on Ubuntu

To install MongoDB, you can follow these general steps:

1. **Update Package Index:**

   ```bash
   sudo apt update


sudo apt update
**Install MongoDB:** 
Once the package index is updated, you can install MongoDB using the package manager. In Ubuntu, MongoDB is available in the default repositories, so you can install it with:

sudo apt install mongodb
**Verify Installation:**
After installation, you can verify MongoDB is running by checking its status:

sudo systemctl status mongodb
If MongoDB is running, you should see an output indicating its status as active.

**Access MongoDB:**
MongoDB should now be installed and running on your system. You can access the MongoDB shell by typing:

mongo
This will open the MongoDB shell where you can interact with the database.

