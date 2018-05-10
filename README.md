# langauge modeling with RNNs in tensorflow

I built it with 3 stacked GRUs ..text8 as dataset for word level language model .. aslo tried character level language modeling on linux source code :D by appending some of linux c files and results are so fun :D

I included only the trained model for linux source code in this repository .. I had 6 more models working on character level(linux source code and shakespere books) with embedding and one hot encoding aslo word level(on text8)

## Example generation for "#inclu" seed :D 

```
de <linux/string.h>
#include <linux/uacdir.h>
#include <linux/mm.h>
#include <linux/module.h>
#include <linux/sched/names.h>
#include <linux/slab.h>
#include <linux/slab.h>
#include <linux/partitull.h>
#include <linux/slab.h>

```

## Example generation for random seed 
```

static void pipe_lock(struct pipe_inode_info *pipe)
{
	struct pipe_inodeinfo *ipimap = null;

	inode = lock_inode(inode);
	status = file_mapping_tree_lock(&fl->fl_file, fl);
	list_for_each_entry(&fl->fl_list, &conf_lock->lock, fl_list)) {
		struct page *page;
		int rc = 0;

		/* copy the page of the page */
		page = local_page_address(page);

		if (pages) {
			page = find_pages_per_page(inode);
			if (page == null)
				goto out_fail;
			len = page_size;
			page = false;
		}
	} else {
		/*
		 * if we've active a page to be a page of a single page and the state of the
		 * request as we're not a possible to avoid any operation the one of
		 * the policy.  if we don't want to specify
		 * a no longer the non-locked page is allocated and we are not
		 * a complete and
		 * the page is a pointer to the leaf page and the page is a caller and the new page
		 * and the page is already already allocated and we're already the lock.
		 */
		if (page->index) {
			/* if we can't allocate an extended page in this leaf. */
			page->index = page_size;
			put_page(page);
			ret = -einval;
			goto out;
		}
		page->mapping->a_ops = &pagelocked;
		page->mapping = page;
		put_page(page);
		return -enomem;
	}

	if (!page) {
		page = falloc_extent_map();
		return -enoent;

		/* set the page */
		if (page != pmd)
			ret = -eio;

		if (rc)
			return rc;
		len = page_size(page);
		locked_page->index =
			length - 1;
		len = length;
	}

	/* fill the new page in the parent page */
	page = page_size(page);
	page = page_address(page);
	put_page(page);
	page->mapping->host = file;
	page->mapping->host = falloc_fl;
	ret = falloc_fl_put(page);
	if (ret < 0)
		goto out;

	/* for a pointer to the length. */
	pool = pos;
	inode->i_old_pages[i] = page;
	if (page == null) {
		page->index++;
		ret = -enomem;
		goto out;
	}

	/* find a newly allocated bytes of a node */
	if (pos >= page_size) {
		/* note that we can't alled the page on the page of the page */
		page = null;
		len = page_size;

		/*
		 * if we can't allocate the page and we already have the page
		 * and allowed the page and the non-loop is not already been
		 * a caller and the page is not allowed to allocate the offset
		 */
		inode = old;
		if (!pageuptodate(page)) {
			/*
			 * insert any of transaction or a set of the length of a page of the length.  in the
			 * extent is a page is a part of a non-exact extent to the page and we can point
			 * to the non-extent of an entry.  the page is not already allowed to be
			 * a possible to a partial page as a new entry.
			 */
			if (!(page->index == page->index + 1)) {
				page = false;
				return err_ptr(-enomem, page_start, end);
			}
			if (page == null) {
				page = null;
				end_page_writeback(page);
				ret = page_shift_pages(inode->i_mapping);
				break;
			}
			if (pages[i] == null)
				return -eio;
			else if (!page)
				return;
			page = null;
		}
		if (!pageuptodate(page))
			goto out;
		if (page == null) {
			page = false;
			ret = -enomem;
			page = null;
			goto out;
		}
		extent_start = len - 1;
	}

	/* if we are a page buffer */
	if (buffer_uptodate(page)) {
		/*
		 * if we've already a page before the page isn't allocated to truncate the page
		 * and real the page.
		 */
		page = find_address(page, page_size);
	}

	/* if we are a page that we've already a pointer to this page in the buffer.
	 */
	if (page->index < page_size) {
		page = find_page_container_add(page);
		if (page != page)
			return -einval;
	}
	return 0;
}

```

## Resources

* [karpathy blog post](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
* [colah blog post on LSTM](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* [R2RT blog post](https://r2rt.com/recurrent-neural-networks-in-tensorflow-i.html)
* [R2RT blog post](https://r2rt.com/recurrent-neural-networks-in-tensorflow-ii.html)
* [R2RT blog post on RNNs](https://r2rt.com/written-memories-understanding-deriving-and-extending-the-lstm.html)
* [martin-RNN (repo + video)](https://github.com/martin-gorner/tensorflow-rnn-shakespeare)



