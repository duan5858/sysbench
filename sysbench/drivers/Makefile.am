# Copyright (C) 2004 MySQL AB
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
# 
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# 
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

if USE_MYSQL
MYSQL_DIR = mysql
endif

if USE_DRIZZLE
DRIZZLE_DIR = drizzle
endif

if USE_ORACLE
ORACLE_DIR = oracle
endif

if USE_PGSQL
PGSQL_DIR = pgsql
endif

if USE_NUODB
NUODB_DIR = nuodb
endif

SUBDIRS = $(MYSQL_DIR) $(ORACLE_DIR) $(PGSQL_DIR) $(DRIZZLE_DIR) $(NUODB_DIR)
