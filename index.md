# Privacy Policy for Table Analyzer Artificial Intelligence

**Last Updated: 15 de Marzo del 2026**

This Privacy Policy explains how "Table Analyzer Artificial Intelligence" ("we", "us", or "our") collects, uses, and discloses information about you when you use our Power BI custom visual.

## 1. Information Collection and Use

Table Analyzer Artificial Intelligence is a Power BI custom visual that analyzes your data to automatically visualize data quality issues using intelligent AI algorithms. 

To provide this functionality, the visual may send data (such as selected data points, summaries, or metadata) to external AI services, specifically **OpenAI** and **Google Gemini**, depending on your configuration.

- **Data Processed:** We process the data you explicitly provide or select within the Power BI report when using the visual.
- **External APIs:** The visual requires the `WebAccess` privilege to communicate securely via HTTPS with external AI APIs (OpenAI / Google Gemini). The data sent to these APIs is subject to their respective privacy policies.
- **No Data Storage:** We do not store, retain, or share your data on our own servers. All data processing happens in real-time between your Power BI client and the configured external AI API.

## 2. API Keys

If you provide your own API keys (e.g., OpenAI API Key or Google Gemini API Key) in the visual's formatting pane, these keys are stored securely within your Power BI environment. We do not have access to, nor do we collect, your API keys.

## 3. Third-Party Services

This visual interacts with third-party services:
- **OpenAI:** [OpenAI Privacy Policy](https://openai.com/policies/privacy-policy)
- **Google:** [Google Privacy Policy](https://policies.google.com/privacy)

Please review their privacy policies to understand how they handle the data transmitted through their APIs.

## 4. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page.

## 5. Contact Us

If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us. Please refer to our Support Document for contact information.



# Support for Table Analyzer Artificial Intelligence

Thank you for using the "Table Analyzer Artificial Intelligence" Power BI custom visual. We are committed to providing you with an excellent experience.

## Getting Started

1. **Installation:** Import the `.pbiviz` file into your Power BI report via the "Import a visual from a file" option.
2. **Setup:** Open the formatting pane of the visual to configure your API keys for the AI providers (OpenAI or Google Gemini).
3. **Usage:** Map your data fields into the visual's data roles to start analyzing and visualizing data quality issues.

## Frequently Asked Questions (FAQ)

**Q: Why do I see a "Model Not Found" error when using Google Gemini?**
A: Please ensure you are using the correct API endpoint. Our visual requires the standard `v1` endpoint (not `v1beta`). Make sure your API key has access to the specified model (e.g., `gemini-1.5-flash`).

**Q: How do I customize the generated insights?**
A: You can configure the system prompts and AI parameters in the visual's formatting pane. Ensure your rules and settings are separated correctly (e.g., by commas or newlines if applicable).

**Q: Where does my data go?**
A: Data is processed in real-time between your Power BI client and the external API (OpenAI or Google Gemini) you configured. We do not store or track any of your data. Please see our [Privacy Policy](./PRIVACY_POLICY.md) for more details.

**Q: Why doesn't the visual display properly?**
A: Table Analyzer Artificial Intelligence requires the `WebAccess` privilege to communicate with external APIs. If your organizational settings block external web requests from custom visuals, the visual will fail to retrieve insights. Check with your Power BI administrator.

## Troubleshooting

1. **Verify API Keys:** Ensure that the API keys entered in the formatting pane are valid, have not expired, and have the correct permissions.
2. **Network Access:** Ensure that your network environment allows outbound HTTPS connections to `api.openai.com` or `generativelanguage.googleapis.com`.
3. **Visual Size:** We recommend resizing the visual container to allow the responsive layout (KPI cards and data tables) to render correctly without cutting off information.

## Contact Information

For further assistance, bug reports, or feature requests, please reach out to us:

- **Email Support:** [angpach@live.com]
  
Please provide as much detail as possible, including error messages, when reaching out for support.
