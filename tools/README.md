# Excel Tools by Aden Ansari

Three free Excel tools. No installation. No subscription.

The first two are complete macro-enabled workbooks — open the file, enable macros, follow the built-in help sheet. The third is a single function you paste into your own workbook.

> **Note on macros:** The two workbooks (`.xlsm`) are macro-enabled. After downloading, right-click the file → Properties → tick **Unblock** (Windows blocks macros in downloaded files by default), then open in Excel and enable macros. The Currency Converter is a `.txt` file — copy the code and paste it into a module (steps below).

---

## 1. Credit Control Manager

**[⬇ Download Credit-Control-Manager.xlsm](https://github.com/adanansarifullstack/adanansari/raw/main/tools/Credit-Control-Manager.xlsm)**

### What it is

An Excel tool that tells you which customer will become your next bad debt.

Built by an accountant who chases real debtors every week. Not a template. A working system. One macro-enabled workbook.

### What it does

Drop in your Tally ledger exports. The tool reads them for you. For every customer, it works out four things:

- How fast they actually pay you — to the day
- How much of their dues they have ever cleared
- How old their unpaid balance really is
- Whether their balance reconciles with your books

Then it gives each customer a **risk score out of 100**. Safe customers get a recommended credit limit. Risky ones get a warning. Critical ones get flagged as projected bad debt — before the money is gone.

There's more. Paste your full debtors list and it builds a **work queue**: top 10 biggest balances flagged first. Tick them off, the next 10 appear. You always know who to chase today.

One click builds a management report — every metric explained in plain English, so your boss understands it without asking you. One click clears everything for the next cycle.

### How it will help

- Stop guessing who deserves credit. Know it.
- Your biggest exposures get chased first, not whoever called loudest.
- Bad debts get caught while they are still collectable.
- The credit limit conversation with management becomes a printed report, not an argument.
- Hours of ledger analysis become minutes.

### Who is this for

Accountants and credit controllers drowning in customer ledgers. Small business owners selling on credit without a credit policy. Trading businesses — building materials, FMCG, spare parts — where 20 customers hold 80% of your money. Finance managers who need to justify credit decisions on paper.

If you sell on credit and track it in Tally or Excel, this was built for you.

---

## 2. Attendance & Salary Sheet

**[⬇ Download Attendance-Salary-Sheet.xlsm](https://github.com/adanansarifullstack/adanansari/raw/main/tools/Attendance-Salary-Sheet.xlsm)**

### What it is

A complete attendance and payroll system inside one Excel file.

Employee database, attendance register, and salary calculation — connected and automated. No HR software fees. No learning curve. Just Excel, working harder than you thought it could.

### What it does

- Keeps a proper **employee database — with photographs**. Add, update, or remove staff through simple forms, not messy cells.
- Tracks daily attendance in a clean register.
- Does the part everyone dreads: the **payout calculation**. Attendance flows into salary automatically. Days worked, days absent, payable amount — computed, not typed.
- An **admin lock** hides the sensitive sheets from casual eyes. One click hides, one click reveals.
- A built-in **help sheet** means anyone on your team can run it.

### How it will help

- Salary day stops being a two-day exercise.
- Attendance disputes end — the register is the record.
- Calculation errors disappear, and so do the overpayments they cause.
- New staff onboard in minutes with a proper database entry, photo included.
- Your salary data stays private, even on a shared computer.

### Who is this for

Small and medium businesses running payroll manually. Shops, workshops, contractors, and trading firms with 5 to 100 staff. Accountants handling payroll for multiple clients. Any owner who has ever paid a salary twice — or late — because of a spreadsheet mess.

If payroll eats your month-end, this gives it back.

---

## 3. Currency Converter (Amount in Words)

**[⬇ Get the code — Currency-Converter.txt](https://github.com/adanansarifullstack/adanansari/raw/main/tools/Currency-Converter.txt)**

### What it is

One Excel function that writes any amount in words — the way invoices and cheques demand it.

USD, AED and INR. Dollars and Cents, Dirhams and Fils, Rupees in Lakhs and Crores. Not a workbook to open — a single function you paste in once and keep forever.

### What it does

You type one formula. It hands back the words.

- `=CurrencyInWords(1250.50, "USD")` → One Thousand Two Hundred Fifty Dollars and Fifty Cents Only
- `=CurrencyInWords(500.75, "AED")` → Five Hundred Dirhams and Seventy Five Fils Only
- `=CurrencyInWords(150000, "INR")` → One Lakh Fifty Thousand Rupees Only

It knows each currency properly (Dollars/Cents, Dirhams/Fils, Rupees/Paise), uses the right number system for each (Millions and Billions for USD/AED, Lakhs and Crores for INR), reads the decimals as minor units, and closes every amount with **"Only"** — exactly how a cheque or invoice needs it. Leave the currency out — `=CurrencyInWords(100)` — and it defaults to USD.

### Before you use it — about 60 seconds, one time

1. Open the code file and **copy everything** (Ctrl+A, then Ctrl+C).
2. In your Excel workbook, press **Alt+F11** to open the VBA editor.
3. Menu: **Insert → Module**. Click the blank window and paste (Ctrl+V).
4. Close the editor (Alt+Q) and **save your file as Excel Macro-Enabled Workbook (.xlsm)**.

Then type `=CurrencyInWords(...)` in any cell. If a cell shows **#NAME?**, macros are off or the code wasn't pasted in.

### How it will help

- Invoices, cheques and payment vouchers get their amount-in-words line without a second thought.
- No more typing long amounts by hand — and no more mismatches between the figures and the words.
- It works inside any workbook you already have — your invoice template, your voucher, your cheque sheet.
- One function covers your UAE work and your India work both.

### Who is this for

Accountants and cashiers who write cheques, invoices and payment vouchers. Anyone billing in Dollars, Dirhams or Rupees who needs the words spelled correctly. Businesses working across the UAE and India, switching between Western and Indian number systems.

If you have ever typed "Dirhams and Fils" by hand on an invoice, this ends that.

---

## Need it to work your way?

Every business runs differently. These tools can be rebuilt around yours. Different ledger format. Extra reports. Your company branding. New features entirely.

**Mail me what you need:** adanansari1234@gmail.com

You describe the problem. I build the Excel that solves it.

*Built by Adan Ansari. Finance brain. Writer's voice.*
