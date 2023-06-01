<h1> v1.1 - Release Date:2023-MAY-12</h1>

<h5>BUG FIXES</h5>
<ol>
<li>Merge Record Issue Fixed In Data Load Process Group.</li>
<li>Adjusted Max Bin Age Of Merge Content To 152 sec w.r.t Fetch Cache Run Schedule In Connector.</li>
<li>Adjusted Max Bin Age Of Merge Record To 60 sec In Data Load.</li>
<li>Set the Include Header Line Attribute Value To False For Csv Record Set Writer In Data Load</li>
</ol>
<h5>ENHANCEMENTS</h5>
1.Stats Insert To Statistics Table For failed Flow Files Reporting In Connector ANd Data Load.
2.Fetch Cache Execution To Run From All Nodes Instead of Primary Node.

<h5>CONFIG CHANGES</h5>
1. Removed the depricated sources "invoicepayment" and "refundinvoicepayment" From All The Tenants.
2. Added Payment Part Entity To All The Tenants.
3. Source Type changes For All The Sources.

<h5>COSMETIC CHANGES</h5>
1.Re-Arranged The Flow Groups In Hexagonal Format Instead Of Linear Presentation.

##############  v1.0 - Release Date:2023-MAY-10
Initial version Release For Both Connector And Data Load
