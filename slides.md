<!-- .slide: data-background="diving-1600668.jpg" class="whiter" -->
# Binx.io

Welcome

---

# List

* **One**. Lorem ipsum.
* **Two**. Lorem dolor.
* **Three**. Lorem lorem.

---

```yml
invoice: 34843
date: 2001-01-23
bill-to: &id001
    given  : Chris
    family : Dumars
    address:
        lines: |
            458 Walkman Dr.
            Suite #292
        city    : Royal Oak
        state   : MI
        postal  : 48046
ship-to: *id001
product:
    - sku         : BL394D
      quantity    : 4
      description : Basketball
      price       : 450.00
    - sku         : BL4438H
      quantity    : 1
      description : Super Hoop
      price       : 2392.00
tax  : 251.42
total: 4443.52
comments: >
    Late afternoon is best.
    Backup contact is Nancy
    Billsmer @ 338-4338.
```

notes:
blaat

---

```python
import boto3

def this_is_a_test(blaat):
    return blaat

ec2 = boto3.client('ec2')
# Retrieves all regions/endpoints that work with EC2
response = ec2.describe_regions()
print('Regions:', response['Regions'])
# Retrieves availability zones only for region of the ec2 object
response = ec2.describe_availability_zones()
print('Availability Zones:', response['AvailabilityZones'])
```

---

<!-- .slide: data-background="diving-1600668.jpg" class="whiter" -->
# Binx.io

End