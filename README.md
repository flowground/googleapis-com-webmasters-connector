# ![LOGO](logo.png) Search Console **flow**ground Connector

## Description

A generated **flow**ground connector for the Search Console API (version v3).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/webmasters/v3/swagger.json<br/>
Generated at: 2019-05-07T17:42:07+03:00

## API Description

View Google Search Console data for your verified sites.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists the user's Search Console sites.

*Tags:* `sites`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Removes a site from the set of the user's Search Console sites.

*Tags:* `sites`

#### Input Parameters
* `siteUrl` - _required_ - The URI of the property as defined in Search Console. Examples: http://www.example.com/ or android-app://com.example/ Note: for property-sets, use the URI that starts with sc-set: which is used in Search Console URLs.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves information about specific site.

*Tags:* `sites`

#### Input Parameters
* `siteUrl` - _required_ - The URI of the property as defined in Search Console. Examples: http://www.example.com/ or android-app://com.example/ Note: for property-sets, use the URI that starts with sc-set: which is used in Search Console URLs.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Adds a site to the set of the user's sites in Search Console.

*Tags:* `sites`

#### Input Parameters
* `siteUrl` - _required_ - The URL of the site to add.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Query your data with filters and parameters that you define. Returns zero or more rows grouped by the row keys that you define. You must define a date range of one or more days.<br/>
> <br/>
> When date is one of the group by values, any days without data are omitted from the result list. If you need to know which days have data, issue a broad date range query grouped by date for any metric, and see which day rows are returned.

*Tags:* `searchanalytics`

#### Input Parameters
* `siteUrl` - _required_ - The site's URL, including protocol. For example: http://www.example.com/
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the sitemaps-entries submitted for this site, or included in the sitemap index file (if sitemapIndex is specified in the request).

*Tags:* `sitemaps`

#### Input Parameters
* `siteUrl` - _required_ - The site's URL, including protocol. For example: http://www.example.com/
* `sitemapIndex` - _optional_ - A URL of a site's sitemap index. For example: http://www.example.com/sitemapindex.xml
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a sitemap from this site.

*Tags:* `sitemaps`

#### Input Parameters
* `feedpath` - _required_ - The URL of the actual sitemap. For example: http://www.example.com/sitemap.xml
* `siteUrl` - _required_ - The site's URL, including protocol. For example: http://www.example.com/
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves information about a specific sitemap.

*Tags:* `sitemaps`

#### Input Parameters
* `feedpath` - _required_ - The URL of the actual sitemap. For example: http://www.example.com/sitemap.xml
* `siteUrl` - _required_ - The site's URL, including protocol. For example: http://www.example.com/
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Submits a sitemap for a site.

*Tags:* `sitemaps`

#### Input Parameters
* `feedpath` - _required_ - The URL of the sitemap to add. For example: http://www.example.com/sitemap.xml
* `siteUrl` - _required_ - The site's URL, including protocol. For example: http://www.example.com/
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a time series of the number of URL crawl errors per error category and platform.

*Tags:* `urlcrawlerrorscounts`

#### Input Parameters
* `category` - _optional_ - The crawl error category. For example: serverError. If not specified, returns results for all categories.
    Possible values: authPermissions, flashContent, manyToOneRedirect, notFollowed, notFound, other, roboted, serverError, soft404.
* `latestCountsOnly` - _optional_ - If true, returns only the latest crawl error counts.
* `platform` - _optional_ - The user agent type (platform) that made the request. For example: web. If not specified, returns results for all platforms.
    Possible values: mobile, smartphoneOnly, web.
* `siteUrl` - _required_ - The site's URL, including protocol. For example: http://www.example.com/
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists a site's sample URLs for the specified crawl error category and platform.

*Tags:* `urlcrawlerrorssamples`

#### Input Parameters
* `category` - _required_ - The crawl error category. For example: authPermissions
    Possible values: authPermissions, flashContent, manyToOneRedirect, notFollowed, notFound, other, roboted, serverError, soft404.
* `platform` - _required_ - The user agent type (platform) that made the request. For example: web
    Possible values: mobile, smartphoneOnly, web.
* `siteUrl` - _required_ - The site's URL, including protocol. For example: http://www.example.com/
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Marks the provided site's sample URL as fixed, and removes it from the samples list.

*Tags:* `urlcrawlerrorssamples`

#### Input Parameters
* `category` - _required_ - The crawl error category. For example: authPermissions
    Possible values: authPermissions, flashContent, manyToOneRedirect, notFollowed, notFound, other, roboted, serverError, soft404.
* `platform` - _required_ - The user agent type (platform) that made the request. For example: web
    Possible values: mobile, smartphoneOnly, web.
* `siteUrl` - _required_ - The site's URL, including protocol. For example: http://www.example.com/
* `url` - _required_ - The relative path (without the site) of the sample URL. It must be one of the URLs returned by list(). For example, for the URL https://www.example.com/pagename on the site https://www.example.com/, the url value is pagename
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves details about crawl errors for a site's sample URL.

*Tags:* `urlcrawlerrorssamples`

#### Input Parameters
* `category` - _required_ - The crawl error category. For example: authPermissions
    Possible values: authPermissions, flashContent, manyToOneRedirect, notFollowed, notFound, other, roboted, serverError, soft404.
* `platform` - _required_ - The user agent type (platform) that made the request. For example: web
    Possible values: mobile, smartphoneOnly, web.
* `siteUrl` - _required_ - The site's URL, including protocol. For example: http://www.example.com/
* `url` - _required_ - The relative path (without the site) of the sample URL. It must be one of the URLs returned by list(). For example, for the URL https://www.example.com/pagename on the site https://www.example.com/, the url value is pagename
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-webmasters-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
