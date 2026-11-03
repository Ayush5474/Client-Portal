# Client-Portal
It’s an internal portal where your team keeps all your current clients in one place. Each client gets a profile with their full history, so nobody has to dig through spreadsheets, emails or LinkedIn to find it.

Core features

1.Client database. You add and store your current clients: company name, contact people, industry, contact details, status and so on. It can also take a bulk import from Excel or CSV.

2.Client history from LinkedIn. For each client or contact, the portal pulls in professional background (current role, past roles, company details, job changes), so you know who you’re dealing with.

3.Employee updates. Your employees can edit client information, add notes, log calls and meetings, and correct outdated details. Every change is recorded with who made it and when.

4.One profile per client. Opening a client shows a single page with their details, LinkedIn background, interaction timeline and notes.

5.Search and filter. You can look up clients by name, company, industry or status.

Who uses it
1.Employees view and update client records.

2.Admins manage users, permissions and data imports.

The LinkedIn part needs a decisio
LinkedIn doesn’t allow scraping profiles, and its official API gives only limited access. There are a few workable options:

1.Official LinkedIn API / partner program. This is compliant but restricted.
2. A third-party data provider with a licensed API, such as Proxycurl-style enrichment services. This gives the most complete data and costs money.
3. Employees paste or enter the LinkedIn URL and key details. This is the simplest start, and automation can be added later.
