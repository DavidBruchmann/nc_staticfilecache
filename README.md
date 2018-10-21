Static File Cache (nc_staticfilecache)
======================================
**TYPO3 extension nc_staticfilecache**  

Transparent static file cache solution using mod_rewrite and mod_expires.  
Increase response times for static pages by a factor of up to 230!!!
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
Versions 1.0.0 - 3.6.0 have been completely provided by the `Static File Cache team`.   
These Versions have been downloaded here: 
 - https://extensions.typo3.org/extension/nc_staticfilecache/  
 - https://github.com/TYPO3-extensions/nc_staticfilecache  

The versions provided here are copies but versioned and tagged with git,
with this additional text-file `README.md` and **composer-support**.  

To install via composer use:  
```
composer require wdb/nc_staticfilecache
```

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
3.6.0 / stable  
March 23, 2016	
 - Now requires PHP 5.5 or higher, due to many code cleanups incl. PSR-2.  
 - [FEATURE] Add TSFE pageCacheTags to our own cache.  
 - Add nginx configuration to documentation.  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
3.5.0 / stable  
December 28, 2015  
  Various bugfixes and code cleanups.  
  All currently known issues have been resolved.  
  Thanks to Tim Lochmueller for continued contributions!  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
3.4.1 / stable  
September 02, 2015  
**NOTE: .htaccess changes are needed when upgrading! Please refer to the manual!**  
 - Fix https://forge.typo3.org/issues/66842  
 - Remove the ValidProtocol Rule  
 - Add a security rule to prevent direct calls of static cache entries  
 - Remove the dummy htaccess file  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
3.3.1 / stable  
May 13, 2015  
 - Finished migration to CachingFramework.  
 - Compatibility until TYPO3 7.2.  
 - Thanks to Tim Lochmueller.  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
3.2.0 / stable  
April 28, 2015  
 - The TYPO3 CachingFramework is used now.  
 - Cleanup of the Backend module.  
 - Documentation migrated to RestructuredText.  
 - Thanks to Tim Lochmueller for his extensive work.  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
3.0.0 / stable  
April 16, 2015  
 - Vastly rewritten v3.0.0 for TYPO3 6.2.x - 7.1.x.  
 - Thanks to the contributors Tim Lochmüller and Jürgen Kußmann!  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.5.2 / stable  
November 11, 2014  
 - Bugfixes. With thanks to Tim Lochmüller.  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.5.1 / stable  
April 09, 2014  
 - Fixed extension key  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.4.1 / stable  
March 11, 2014
 - Bugfix  
 - TYPO3 6.2 compatibility  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.4.0 / stable  
March 07, 2014  
 - Updated to svn v2.3.8 from forge.typo3.org  
 - Integrated TYPO3 6 compatibility adjustments for release as v2.4.0.  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.3.4 / stable  
October 31, 2010  
 - See Changelog  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.3.1 / stable  
May 11, 2008  
 - fixed bug, $timeOutSeconds was set only when $conf[sendCacheControlHeader] was set but used also it $conf[sendCacheControlHeader] was not set . . . This caused expiry time to be 0 if sendCacheControlHeader was not set.  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.3.0 / stable   
June 28, 2007  
 - Now handles external url properly, thanks to Helmut Hummel.  
 - Default exclusion of .css and .xml from cache rewriting.  
 - Put cleaner script back in. Its optional! Allows for static dynamic extensions.  
 - updated manual  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.2.0 / stable  
June 22, 2007  
 - Now supports simulateStaticDocuments, thanks to Marc Hörsken!  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.1.0 / stable  
June 14, 2007  
 - frontend user login detection with own cookie  
 - updated manual  
 - no more negative cache headers  
 - cache headers send on access just like with TYPO3 cache  
 - removal of cleaner script (not needed any longer because of new header code)  
 - added TODO to manual  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
2.0.0 / stable  
May 03, 2007  
 - Added info module to troubleshoot indexing.  
 - Some minor bugfixes.  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
1.0.0 / stable  
March 15, 2007  
 - Initial release.  
 - Speed up the serving of static pages using mod_rewrite and mod_expires.  
 - Speed increase factor of up to 92.  
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -  
