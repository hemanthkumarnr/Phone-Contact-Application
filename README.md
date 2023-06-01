##############  v1.1 - Release Date:2023-MAY-12
BUG FIXES
1. Merge Record Issue Fixed In Data Load Process Group.
2. Adjusted Max Bin Age Of Merge Content To 152 sec w.r.t Fetch Cache Run Schedule In Connector.
3. Adjusted Max Bin Age Of Merge Record To 60 sec In Data Load.
4. Set the Include Header Line Attribute Value To False For Csv Record Set Writer In Data Load

ENHANCEMENTS
1.Stats Insert To Statistics Table For failed Flow Files Reporting In Connector ANd Data Load.
2.Fetch Cache Execution To Run From All Nodes Instead of Primary Node.

CONFIG CHANGES
1. Removed the depricated sources "invoicepayment" and "refundinvoicepayment" From All The Tenants.
2. Added Payment Part Entity To All The Tenants.
3. Source Type changes For All The Sources.

COSMETIC CHANGES
1.Re-Arranged The Flow Groups In Hexagonal Format Instead Of Linear Presentation.

##############  v1.0 - Release Date:2023-MAY-10
Initial version Release For Both Connector And Data Load
