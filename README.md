Stdheader is vim script that create header in file:

    # **************************************************************************** # 
	#                                                                              #
	#                                                         :::      ::::::::    #
	#    README.md                                          :+:      :+:    :+:    #
	#                                                     +:+ +:+         +:+      #
	#    By: dfedorov <dfedorov@student.unit.ua>        +#+  +:+       +#+         #
	#                                                 +#+#+#+#+#+   +#+            #
	#    Created: 2018/01/03 16:43:51 by dfedorov          #+#    #+#              #
	#    Updated: 2018/01/03 16:43:51 by dfedorov         ###   ########.fr        #
	#                                                                              #
	# **************************************************************************** #


## Installation
### Vundle
Place this in your `.vimrc`:
	
	Plugin 'dfedorov-dev/stdheader'
	    
then run the following in Vim:

	:source %
	:PluginInstall

Also, set your `$USER` and `$MAIL` shell variables.

## Using Stdheader
When file open, use command:

	:Stdheader
