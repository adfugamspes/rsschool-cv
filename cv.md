# Aksana Shor

## Contact information
- **Location:** Haifa, Israel
- **Email:** report.shor@gmail.com
- **Phone number:** +972 53 2222591
- **Discord/Telegram:** @adfugamspes

## Skills

- Java
- Selenium
- Postman
- Appium
- SQL

## Work Experience 

Infinya Packaging Ltd (2024-2025)
packaging and recycled paper products

### Positions
- Quality Control Specialist (11 months) [infinya.co.il](https://www.infinya.co.il/)

YurSpektr LLC, Minsk, Belarus (2016-2021)
online service for lawyers and accountants [ilex.by](https://ilex.by/)

### Positions
- Product Manager (2 years)
- Search Engine Optimization Specialist (1 year 3 months)
- Contract Law Department Specialist (1 year 7 months)

### Responsibilities
 - department management
- customer research/development/support
- documentation writing
- presentations for CEO and customers
- brainstorming for new features 
- software requirements approval
- work with Confluence, JIRA, Kibana
- proofreading/editing of analytical materials on Contract Law

## Education
Software QA Manual & Automation, Tel-Ran
Haifa, Israel, 2025-2026, 330 academic hours

Business Analysis for IT, IT-Academy,
Minsk, Belarus, 2021, 136 academic hours

Bachelor of International Law, 
European Humanities University,
Vilnius, Lithuania, 2012-2016

## Languages
- **English** – Advanced
- **Russian, Belarusian** – Native
- **Hebrew** – Beginner

## Code Example

```
public static String getProperty(String fileName, String key) {
        Properties properties = new Properties();
        try {
            FileInputStream fileInputStream = new FileInputStream
                    ("src/test/resources/properties" + File.separator + fileName);
            properties.load(fileInputStream);
            return properties.getProperty(key);
        } catch (IOException e) {
            System.out.println("exception created");
            e.printStackTrace();
            return null;
        }
    }
```
