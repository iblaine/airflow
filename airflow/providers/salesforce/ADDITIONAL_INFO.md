<!--
 Licensed to the Apache Software Foundation (ASF) under one
 or more contributor license agreements.  See the NOTICE file
 distributed with this work for additional information
 regarding copyright ownership.  The ASF licenses this file
 to you under the Apache License, Version 2.0 (the
 "License"); you may not use this file except in compliance
 with the License.  You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing,
 software distributed under the License is distributed on an
 "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
 KIND, either express or implied.  See the License for the
 specific language governing permissions and limitations
 under the License.
 -->

## Release 2021.3.3

### Breaking changes

* Tableau provider moved to separate 'tableau' provider

You need to install `apache-airflow-backports-providers-tableau` provider additionally to get
Tableau integration working.

# Mysql client requirements

The version of MySQL server has to be 5.6.4+. The exact version upper bound depends
on the version of ``mysqlclient`` package. For example, ``mysqlclient`` 1.3.12 can only be
used with MySQL server 5.6.4 through 5.7.