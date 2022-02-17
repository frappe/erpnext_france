## ERPNext France

App to hold regional code for France, built on top of ERPNext.

### Introduction

ERPNext France aims to support regional customizations for France. The app is built on Frappe, a full-stack, meta-data driven, web framework, and integrates seamlessly with ERPNext, the most agile ERP software.

Some customizations include:
- Transaction Logs -
In order to be compliant with the latest finance law applicable to POS software, ERPNext France automatically registers all sales and payment transactions in a chained log. Additionally, the deletion of sales and payment transactions will also not be permitted, even if the appropriate permissions are given to the user.


- Le Fichier des Écritures Comptables [FEC] -
Since 2014, a legal requirement makes it mandatory for companies operating in France to provide a file of their general accounting postings by fiscal year corresponding to an electronic accounting journal.

For ERPNext France users this file can be generated using this report called Le Fichier des Écritures Comptables [FEC].

### Installation

Using bench, [install ERPNext](https://github.com/frappe/bench#installation) as mentioned here.

Once ERPNext is installed, add ERPNext France app to your bench by running

```sh
$ bench get-app https://github.com/frappe/erpnext_france.git
```

After that, you can install the app on required site (let's say demo.com )by running

```sh
$ bench --site demo.com install-app erpnext_france
```

### License

GNU GPL V3. See [license.txt](https://github.com/frappe/erpnext_france/blob/develop/license.txt) for more information.
