# Release 5.0.22

- **Download issue with records based on Maximo relationships**: 
  This release addresses a critical issue where records linked via specific Maximo relationships could not be properly downloaded. The problem caused incomplete or missing data during export or download processes when records were associated with one another through Maximo's relationship configurations.

  Key aspects of this fix include:
  
  - **Comprehensive download of related records**: Before this fix, users experienced issues where records tied together through certain Maximo relationships (such as parent-child relationships between assets, locations, or work orders) would fail to download completely, or related data would be omitted. The issue has now been resolved, ensuring that all associated records are correctly included during download operations.
  
  - **Improved handling of complex relationships**: Maximo's ability to define complex relationships between different entities, such as hierarchical work orders, asset relationships, or inventory transactions, now functions smoothly in data exports. This fix improves the reliability of downloading comprehensive datasets, which is particularly important for users who need to transfer data across systems or for reporting purposes.
  
  - **Performance optimization**: Alongside fixing the issue, the download process has been optimized for speed and efficiency, particularly when handling large datasets with extensive relationships. This enhancement ensures that downloads of related records are not only complete but also processed in a timely manner, avoiding delays during export operations.
  
  - **Applicability across modules**: The fix applies across all Maximo modules where relationships between records are critical, such as assets, work orders, locations, and inventory. Whether users are exporting records for reporting, data analysis, or integration with other systems, this fix ensures data consistency and completeness.

  **Benefits:**
  - **Reliable data exports**: Users can now confidently download complete sets of related records without encountering missing or incomplete data.
  - **Improved data integrity**: Ensures that relationships between records are maintained during exports, preventing broken links or mismatched data.
  - **Faster and more efficient downloads**: Optimized processing times reduce wait periods for large downloads involving complex relationships.
