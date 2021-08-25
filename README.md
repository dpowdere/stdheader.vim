Stdheader is a vim script that prepends the [standard header][42] to a file
according to Ecole 42 requirements:

    # **************************************************************************** #
    #                                                                              #
    #                                                         :::      ::::::::    #
    #    README.md                                          :+:      :+:    :+:    #
    #                                                     +:+ +:+         +:+      #
    #    By: zaz <zaz@42.fr>                            +#+  +:+       +#+         #
    #                                                 +#+#+#+#+#+   +#+            #
    #    Created: 2017/07/22 18:22:13 by zaz               #+#    #+#              #
    #    Updated: 2017/07/22 18:22:13 by zaz              ###   ########.fr        #
    #                                                                              #
    # **************************************************************************** #

## Installation with Vundle

Place this in your `.vimrc`:

	Plugin 'dpowdere/stdheader.vim'

then run the following in Vim:

	:source %
	:PluginInstall

Also, set your `$USER` and `$MAIL` shell variables.

## Using Stdheader
Use command `:Stdhdr` to add header into a file and `:StdhdrReplace` to
completely replace an existing header.

[42]: https://github.com/42Paris/42header
