# Third Party APIs and Subprocessors

The following table provides an overview of our subprocessors and third-party APIs used to provide our services.  
Each entry includes its primary processing purpose, data access extent, and processing location.

| Subprocessor                 | Purpose                                   | Extent of Data Access                                                                      | Processing Location                               | Security Measures / Data Processing                                                 |
| ---------------------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------- | ----------------------------------------------------------------------------------- |
| **Gemini (Google Cloud AI)** | Generate text responses to prompts        | Portions of provided scripts and audio for response generation (no retention, no training) | United States                                     | [Paid Services Privacy Terms](https://ai.google.dev/gemini-api/terms#paid-services) |
| **Stripe**                   | Payment processing and account handling   | Name, email, billing address, and payment details (not visible to Palaba)                  | United States / EU (depending on customer region) | [Data Processing Agreement](https://stripe.com/en-gb-de/legal/dpa)                  |
| **AssemblyAI**               | Audio transcription                       | Full audio temporarily processed (no retention, no training)                               | United States                                     | [Privacy Policy](https://www.assemblyai.com/legal/privacy-policy)                   |
| **Speechmatics**             | Short-segment transcription               | Short audio clips (a few seconds, no retention, no training)                               | United Kingdom                                    | [Privacy Policy](https://www.speechmatics.com/legal/privacy-policy)                 |
| **PostHog**                  | Product analytics and event tracking      | IP address, user agent, page visits, and interaction events                                | European Union                                    | [Privacy Policy](https://posthog.com/privacy)                                       |
| **Convex**                   | Application database and metadata storage | Metadata (project references, session tokens, and identifiers)                             | United States                                     | [Privacy Policy](https://www.convex.dev/legal/privacy/v2024-03-21)                  |

# Data Processing and Retention

Wherever possible, we use subprocessors in a _transient processing_ model, meaning data is processed only in memory or held briefly for operational tasks without long-term storage.  
For more information on each subprocessor's data handling practices, please refer to the linked privacy policies above, and where applicable to their paid services terms.

All persistent project and account data are stored in the **United States**.  
By using the Service, you understand and agree that your information will be processed in the United States under U.S. privacy law.
