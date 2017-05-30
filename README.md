This is a cart app based on Ruby on Rails book 'Agile Web Development with Rails 5'.

What did I encounter so far?

<ol>
	<li><strong>Issue</strong> <code>method::delete</code> didn't work. Tried to push it with Bang method (add !) after <code>@product.destroy</code>but still didn't work. The solution was restarting macbook. Because somehow i used other terminal with WEBrick building another app and still running as a background. with this app, I use Puma for this app. <strong>Solution: </strong>Restart terminal and only develop one app in a time. <strong>Future task:</strong> Two server running simultanuosly didn't help so much. So I need to find out how to develop two apps in the same machine.</li>
</ol>