# How to See the Read Status in Zotero

Great! The menu is working. Now here's how to see which items are marked as read:

## Method 1: Show the "Read" Column (Recommended)

1. **Right-click on any column header** in your library
   - For example, right-click on "Title", "Creator", "Year", etc.
   
2. **Look for "Read" in the menu** that appears

3. **Check the box next to "Read"**
   - A checkmark should appear

4. **A new "Read" column appears!**
   - Items marked as read will show a ✓ checkmark
   - Unread items will be blank

### Adjust the Column:
- **Move it**: Drag the "Read" column header left or right
- **Resize it**: Drag the edge of the column to make it wider/narrower
- **Hide it**: Right-click any column header and uncheck "Read"

## Method 2: Use the Tags Pane

The plugin uses tags to track read status:
- Items marked as read have a `_read` tag
- Items marked as unread have a `_unread` tag

To see these tags:
1. Look at the **Tags pane** on the left (below Collections)
2. Look for tags starting with underscore: `_read` and `_unread`
3. Click on `_read` to see all read items
4. Click on `_unread` to see all unread items

**Note**: The underscore prefix keeps these tags separate from your regular tags.

## Method 3: Check Individual Items

When you select an item:
1. Look at the **right panel** (item details)
2. Scroll to the **Tags** section
3. You'll see either `_read` or `_unread` tag

## After Installing the Update:

1. **Remove the old plugin**:
   - Tools → Add-ons → Find "Mark as Read" → Remove
   
2. **Restart Zotero**

3. **Install the new version** (the updated .xpi file)

4. **Restart Zotero again**

5. **Enable the Read column**:
   - Right-click any column header → Check "Read"

The Read column should now appear and show checkmarks for items you've marked as read!

## Troubleshooting

**Column not appearing in the list?**
- Make sure you've restarted Zotero after installing the update
- Check Tools → Add-ons to verify the plugin is enabled
- Check Help → Debug Output Logging for errors

**Column appears but no checkmarks?**
- Mark an item as read first (right-click → Mark as Read)
- The checkmark should appear immediately
- If not, try clicking on a different item and back

**Already marked items as read but don't see checkmarks?**
- The tags are still there (`_read` tags)
- The column should show checkmarks once you install this update
- You don't need to re-mark items
