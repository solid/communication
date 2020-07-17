# Social media used 
Solid has a [twitter](https://twitter.com/project_solid) and [mastadon](https://mastodon.online/web/accounts/52488) account. 

To make a suggestion to promote something from the Solid social media [submit a pull request to this repository](https://github.com/solid/social-media)

## The tweets/ folder

To create a new social media post create a new `*.posts` file in this `posts/` folder.

<kbd>[Create new social media post](../../../new/master/?filename=posts/<your-path>.posts)</kbd>

## Example

Create a new file `posts/hello-world.post` with the content

> Hello, world!

You can use subfolders, e.g. `posts/2019-02/hello-world.post`, as long as the file is in the `posts/` folder and has the `.post` file extension

## Create a tweet with a twitter poll

**Note**: The configured twitter account needs to be authorized to use Twitters Ads API in order to send tweets including a poll.

A tweet including a poll must end with 2-4 options in the following format

> Here is some text
>
> ( ) option A  
> ( ) option B  
> ( ) option C  
> ( ) option D

## Notes

- Only newly created files are handled, deletions, updates or renames are ignored.
- `*.tweet` files will not be created for tweets you send out directly from twitter.com
- If you need to rename an existing tweet file, please do so locally using [`git mv old_filename new_filename`](https://help.github.com/en/articles/renaming-a-file-using-the-command-line), otherwise it may occur as deleted and added which would trigger a new tweet.

## Questions?

If you have any further questions or suggestions, please create an issue at https://github.com/gr2m/twitter-together/issues/new
