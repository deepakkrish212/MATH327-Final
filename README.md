# MATH327-Final
This is our (Alec, Deepak, Prana, and Rattanan) final project for MATH 327

Project Idea
- Wealth of Data <br>
"<b>Of particular interest to Sunshine
Companyare time-based patterns in these data, and whether they interact in ways that
will help the company craft successful products.</b>"
    - Key Objectives
        1. inform their online sales strategy
        2. identify potentially important design features that would enhance product desirability
    - Requirements
        1. Analyze the three product data sets provided to identify, describe, and support with
        mathematical evidence, meaningful quantitative and/or qualitative patterns,
        relationships, measures, and parameters within and between star ratings, reviews, and
        helpfulness ratings that will help Sunshine Company succeed in their three new online
        marketplace product offerings.
        2. Use your analysis to address the following specific questions and requests from the
        Sunshine Company Marketing Director:
            - Identify data measures based on ratings and reviews that are most informative
            for Sunshine Company to track, once their three products are placed on sale in
            the online marketplace.
            - Identify and discuss time-based measures and patterns within each data set that
            might suggest that a product's reputation is increasing or decreasing in the
            online marketplace.
            - Determine combinations of text-based measure(s) and ratings-based measures
            that best indicate a potentially successful or failing product.
            - Do specific star ratings incite more reviews? For example, are customers more
            likely to write some type of review after seeing a series of low star ratings?
            - Are specific quality descriptors of text-based reviews such as 'enthusiastic',
            'disappointed', and others, strongly associated with rating levels?


- Data Definition
    - Data Set Definitions
        - marketplace (string): 2 letter country code of the marketplace where the review
was written.
        - customer_id (string): Random identifier that can be used to aggregate reviews
written by a single author.
        - review_id (string): The unique ID of the review.
        - product_id (string): The unique Product ID the review pertains to.
        - product_parent (string): Random identifier that can be used to aggregate
reviews for the same product.
        - product_title (string): Title of the product.
        - product_category (string): The major consumer category for the product.
        - star_rating (int): The 1-5 star rating of the review.
        - helpful_votes (int): Number of helpful votes.
        - total_votes (int): Number of total votes the review received.
        - vine (string): Customers are invited to become Amazon Vine Voices based on
    the trust that they have earned in the Amazon community for writing accurate
    and insightful reviews. Amazon provides Amazon Vine members with free
    copies of products that have been submitted to the program by vendors.
    Amazon doesn't influence the opinions of Amazon Vine members, nor do they
    modify or edit reviews.
        - verified_purchase (string): A "Y" indicates Amazon verified that the person
    writing the review purchased the product at Amazon and didn't receive the
    product at a deep discount.
        - review_headline (string): The title of the review.
        - review_body (string): The review text.
        - review_date (bigint): The date the review was written.
