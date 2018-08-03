---
seo:
  title: analytics-and-reporting Overview
  description: View and filter all of your SendGrid account email statistics.
  keywords: analytics-and-reporting, SendGrid analytics-and-reporting, analytics-and-reporting Overview, analytics-and-reporting UI
title: Statistics Overview
group: statistics
weight: 100
layout: page
navigation:
  show: true
---

<call-out>

Parent accounts will see aggregated stats for their account and all subuser accounts. Subuser accounts will only see their own stats.

</call-out>

<p>
Tracking your emails is an important part of being a good sender and learning about how your users interact with your email. This includes everything from basics of clicks and opens to looking at which browsers and mailbox providers your customers use.
</p>
<p>
We have broken up stats in specific ways so that you can get at-a-glance data, as well as allowing you to get into the details of how your email is being used.
</p>

- [Available Email analytics-and-reporting Reports](#-Available-Email-analytics-and-reporting-Reports)
- [Metrics](#-Metrics)
- [analytics-and-reporting_Filter](#-analytics-and-reporting-Filters)
- [Top_5_Categories](#-Top-5-Categories)

## 	Available Email analytics-and-reporting Reports
 	
<call-out>

The timezone for stats pages is set in your [account settings]({{root_url}}/help-support/account-and-settings/account/).

</call-out>

<p>
<strong><a href="#-analytics-and-reporting-Filters"Overview</a></strong> - The overview is your at-a-glance stats. We give you the highlight reel so that you can keep an eye out for any issues and make sure you’re on the right track.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/global/">Global Stats</a></strong> - All of your stats, aggregated in one place so you can see the high level view of everything.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/categories/">Category Stats</a></strong> - You can define your categories when you send, so that you can view your email performance by category later.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/category-comparison/">Category Comparison</a></strong> - Compare the performance of emails from up to 10 categories against each other.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/subuser/">Subuser Stats</a></strong> - You can segment your email to be sent by different subusers, which allows you to compare how each type or subset of your email is performing.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/subuser-comparison/">Subuser Comparison</a></strong> - Compare the performance of emails from up to 10 subusers against each other.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/geographic/">Geographical</a></strong> - See where you get the best engagement and compare engagement by geographical region.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/device/">Email Clients and Devices</a></strong> - Find out which applications and devices your recipients use to view your mail and see the stats for each.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/mailbox-provider/">Mailbox Provider Stats</a></strong> - See all the stats for the mailbox providers your recipients use.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/mailbox-provider-comparison/">Mailbox Provider Comparison</a></strong> - Compare the performance of emails by statistic and provider.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/browser/">Browser Stats</a></strong> - See all the stats for the web browsers your users view your emails from.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/browser-comparison/">Browser Comparison</a></strong> - Compare the performance of your emails by statistic and browser.
</p><p>
<strong><a href="{{root_url}}/help-support/analytics-and-reporting/inbound-parse/">Parse Webhook</a></strong> - View the number of requests you have received via the Parse Webhook.
</p>

## 	Metrics
 	<p>
On the available statistics reports, you will find that your deliverability is broken down by the following metrics. Each one gives you a different piece of information about how SendGrid or your recipients interact with your email.
</p>
<p>
<strong><a href="{{root_url}}/glossary/blocks/">Blocks</a></strong> - The number of emails that were not allowed to be delivered by ISPs.
</p><p>
  <strong><a href="{{root_url}}/glossary/bounces/">Bounces</a></strong> - The number of emails that bounced instead of being delivered.
</p><p>
  <strong><a href="{{root_url}}/glossary/clicks/">Clicks</a></strong> - The number of links that were clicked in your emails.
</p><p>
  <strong><a href="{{root_url}}/glossary/deliveries/">Deliveries</a></strong> - The number of emails SendGrid was able to confirm were actually delivered to a recipient.
</p><p>
  <strong>Invalid Emails</strong> - The number of recipients that you sent emails to, who had malformed email addresses or whose mail provider reported the address as invalid.
</p><p>
  <strong><a href="{{root_url}}/glossary/opens/">Opens</a></strong> - The total number of times your emails were opened by recipients.
</p><p>
  <strong><a href="{{root_url}}/glossary/request/">Requests</a></strong> - The number of emails you requested to send via SendGrid.
</p><p>
  <strong><a href="{{root_url}}/glossary/spam-reports/">Spam Reports</a></strong> - The number of recipients who marked your email as spam.
</p><p>
  <strong><a href="{{root_url}}/glossary/spam-reports/">Spam Report Drops</a></strong> - The number of emails dropped by SendGrid because that recipient previously marked your emails as spam.
</p><p>
  <strong><a href="{{root_url}}/glossary/opens/">Unique Opens</a></strong> - The number of unique recipients who opened your emails.
</p><p>
  <strong><a href="{{root_url}}/glossary/clicks/">Unique Clicks</a></strong> - The number of unique recipients who clicked links in your emails.
</p><p>
  <strong>Unsubscribes</strong> - The number of recipients who unsubscribed from your emails.
</p><p>
  <strong>Unsubscribe Drops</strong> - The number of emails dropped by SendGrid because the recipient unsubscribed from your emails.
</p>

## 	analytics-and-reporting Filters
 	<p>
These filters are available on most of the statistics pages. They will help you see your stats in more or less details, depending on your needs.
</p>

<p>
  <strong>Metric Filters</strong> - You can select all of the metrics or only some of them.
</p><p>
  <strong>Date Filters</strong> - To display stats between specific dates, choose your date range.
</p><p>
  <strong>Grouping Filter</strong> - Display stats grouped by day, week, or month.
</p>

## 	Top 5 Categories
 	
<p>
  The Top 5 Categories report allows you to see your top 5 most used categories by number of requests. Switch your view by actual number of emails or percentage using the toggle at the top right of this section.
</p>

## 	Additional Resources
 	
<ul>
  <li><a href="https://sendgrid.com/docs/API_Reference/Web_API_v3/Stats/index/" target="_blank">Stats Overview</a></li>
  <li><a href="https://sendgrid.com/docs/API_Reference/Web_API/Statistics/index/" target="_blank">General analytics-and-reporting</a></li>
  <li><a href="https://sendgrid.com/docs/API_Reference/Web_API/Statistics/statistics_advanced/" target="_blank">Advanced analytics-and-reporting</a></li>
</ul>