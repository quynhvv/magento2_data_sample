# magento2_data_sample
This data sample compatible with Magento2 version 0.42.0 beta9
Step to use:
  1 - Import the magento2_data_sample.sql to your Database. Install Magento2 with this database.
  2 - Copy the media files from folder /pub/media/catalog to /pub/media/ in your Magento2 website.
  3 - In commadn line window, go to the folder PATH_TO_YOUR_WEB_ROOT_FOLDER\your_magento2_web_root_folder\dev\shell\
      and type command line: php indexer.php reindexall
      and press enter key to re-index all data in your Magento2 website.
