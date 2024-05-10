# Reuse Features in Ixiasoft DITA CMS

[toc]

Content reuse is a powerful tool in content creation, saving significant time and effort by eliminating the need to recreate identical pieces of content. It also ensures consistency across documents, preventing discrepancies that can confuse readers. By reusing content, teams can focus on creating new, valuable content instead of duplicating efforts. This efficiency can lead to improved productivity and content quality.

[**Ixiasoft DITA CMS**](https://www.ixiasoft.com/) provides a suite of features designed to streamline this process.

> **_Note_**
>
> _Examples provided on this page are based on a_ **_[SupplyChain Solutions](https://bing.com/search?q=SupplyChain+Solutions"%20\t%20"_blank)_** _company, that manages supply chain operations for various clients and often needs to create variant documents._

## Content References (Conref)

Content References, or Conref, allow you to create specific pieces (or snippets) of content that can be referenced across multiple topics in DITA. The reused content, facilitated by Conref, becomes a part of the topics into which it is inserted, enhancing their comprehensiveness and consistency. These enriched topics can be included in the same map (a collection of topics organized and linked together) or in different maps.

### Example

**SupplyChain Solutions** created a standard shipping policy in one location. This policy was inserted it into multiple topics using a Conref. These topics were included in various maps based on the needs of different clients.

### More Information

- For additional information on using Conrefs, refer to the [Ixiasoft DITA CMS Conref Guide](https://www.ixiasoft.com/documentation/IXIASOFT_CCMS/6.8/User_Guides_Advanced_User_Standard/en/lar1396892881040.html"%20\t%20"_blank).
- Read about the equivalent feature in [MadCap Flare: Snippet](https://www.madcapsoftware.com/blog/guest-post-madcap-flare-101-8-variables-and-snippets/"%20\t%20"_blank).

## Key References (Keyref)

Key References, or Keyref, allow you to create a placeholder for content that can be replaced with the actual content at the time of publishing. This feature is useful when the content varies between clients.

### Example

**SupplyChain Solutions** uses a Keyref for the client’s company name, ensuring the correct name is inserted into each client’s documents at the time of publishing.

### More Information

- For additional information on using Keyrefs, refer to the [Ixiasoft DITA CMS Keyref Guide](https://www.ixiasoft.com/documentation/IXIASOFT_CCMS/5.0/User_Guides_Advanced_User_DRM/per1389986050420_7.html"%20\t%20"_blank).
- Read about the equivalent feature in [MadCap Flare: Variable](https://www.madcapsoftware.com/blog/guest-post-madcap-flare-101-8-variables-and-snippets/"%20\t%20"_blank).

## Conditional Processing (Profiling)

Conditional Processing allows you to mark specific sections within a topic for inclusion or exclusion based on certain project-wide conditions. These conditions, which can be things like product versions, audience types, or geographic locations, can be applied to specific sections within individual topics. This allows for greater flexibility and precision in content customization.

### Example

For instance, SupplyChain Solutions uses Conditional Processing to include specific sections such as **Return Policies** or **Warranty Information** in a topic for one client, and exclude them for another client who does not require these details.

### More Information

- For additional information on using Conditional Processing, refer to the [Ixiasoft DITA CMS Profiling Guide](https://www.ixiasoft.com/documentation/IXIASOFT_CCMS/6.8/User_Guides_Advanced_User_Standard/en/per1389986186479.html"%20\t%20"_blank).
- Read about the equivalent feature in [MadCap Flare: Conditional Tags](https://www.madcapsoftware.com/blog/tips-and-tricks-using-conditions-in-madcap-flare/"%20\t%20"_blank).

## Topic Reuse

Topic Reuse in Ixiasoft DITA CMS allows you to use the same topic in multiple maps. Each map is a collection of topics organized and linked together to form a cohesive document.

### Example

For instance, **SupplyChain Solutions** uses a topic on **Inventory Management** that is relevant to multiple clients. Instead of duplicating this topic for each client, you can create it once and reuse it in multiple maps.

### More Information

- For additional information on Topic Reuse, refer to the [Ixiasoft DITA CMS Topic Reuse Guide](https://www.ixiasoft.com/documentation/IXIASOFT_CCMS/6.3/User_Guides_Contributors_Standard/en/cab1556029603998.html"%20\t%20"_blank).
- Read about the equivalent feature in [MadCap Flare: Topic Reuse](https://forums.madcapsoftware.com/viewtopic.php?t=28997"%20\t%20"_blank).
