Machine Hour Rate (MHR) Calculator – Cost per Machine Hour, OEE, and Per‑Part Cost

An easy, browser‑based Machine Hour Rate (MHR) calculator that helps manufacturers, SMEs, and job shops compute true cost per machine hour and cost per part. No installation or backend required—open the HTML and start calculating.
What is Machine Hour Rate (MHR)?

Machine Hour Rate is the total cost to run a machine for 1 hour. It combines fixed costs (depreciation, rent, salaries, insurance) and variable costs (power, consumables, tooling) and divides them by the effective productive hours. Knowing MHR lets operations and costing teams:

    Quote parts accurately and protect margins

    Compare machines, shifts, and processes

    Identify cost drivers like energy, tool wear, or downtime

    Run what‑if analyses on utilization and OEE

Why this MHR Calculator?

    100% client‑side: works offline after loading, no data leaves the browser.

    Clear cost breakdown: fixed vs variable costs with monthly totals.

    OEE integration: Availability × Performance × Quality feed effective hours.

    Per‑part costing: uses cycle time or output rate to compute unit cost.

    Export to PDF/Excel: share estimates with management or customers.

    Mobile‑friendly single HTML file—ideal for shop‑floor use.

Core Formulas

    OEE = Availability × Performance × Quality

    Effective Hours = Available Hours × OEE

    Total Monthly Cost = Fixed Costs + Variable Costs

    Machine Hour Rate (MHR) = Total Monthly Cost ÷ Effective Hours

    Cost per Part = MHR × Cycle Time (in hours)

Example:

    Fixed ₹150,000 + Variable ₹50,000 = ₹200,000/month

    Available 300h/month, OEE 70% ⇒ Effective 210h

    MHR = 200,000 ÷ 210 = ₹952.38/hour

    Cycle 180s (0.05h) ⇒ Cost/part ≈ ₹47.62

Who should use it?

    CNC, VMC, HMC, turning, fabrication, molding, casting shops

    Production planners, industrial engineers, and costing teams

    MSMEs optimizing quotes and capacity in India and globally

Inputs You Can Configure

    Time & capacity: shifts/day, hours/shift, working days/month

    OEE: availability losses (breakdowns, setups), performance losses (speed), quality losses (rejections)

    Fixed costs: machine depreciation/lease, floor rent, salaries, AMC, insurance, overhead allocation

    Variable costs: electricity (kW×tariff), tooling, coolant, consumables, indirects

    Process: cycle time, planned scrap, changeover assumptions

Outputs You Get

    Monthly fixed and variable totals

    Effective hours and utilization

    Machine Hour Rate (currency/hour)

    Cost per part (optional)

    PDF/Excel exports for records

Getting Started

    Open index.html (redirects to the latest calculator file), or open the calculator HTML directly.

    Enter cost and OEE inputs in the left pane, review results on the right.

    Export as needed.

Deploy on GitHub Pages

    Visit https://ajinkyaroxx.github.io/MHR_Calculaor/

Tips for Accurate MHR

    Use actual energy meter readings (kWh) for a week; compute average per hour.

    Separate tooling that scales with feed/material from fixed AMC/tooling.

    Update OEE monthly; big swings often come from availability.

    Revisit depreciation or lease terms annually.

FAQ

    Does it need internet? No. It’s a single static HTML with JS; exports use in‑browser libraries.

    Can it handle multiple machines? Duplicate the file per machine or extend the sheet to a comparison view.

    Multiple currencies? Yes—values are numeric; labels can be edited to ₹, $, €, etc.

Roadmap

    Scenario save/load (JSON)

    Multi‑machine comparison dashboard

    Sensitivity sliders (tariff, OEE, cycle time)

    Role‑based presets for operator/manager views

    Dark mode

Contributing

    Issues and pull requests are welcome for UI/UX, formulas, and domain improvements.

    Please keep changes client‑side and privacy‑friendly.

License

Choose a license (MIT recommended) so teams can adopt and adapt it.
SEO Keywords

Machine Hour Rate calculator, MHR calculator, cost per machine hour, OEE cost calculator, CNC costing tool, manufacturing cost calculator, cost per part, shop floor costing, MSME costing India, energy cost per hour, tooling cost, production costing spreadsheet alternative
About

This project aims to give manufacturers a transparent, practical MHR tool without Excel dependencies or complex software—fast, accurate, and shareable.
