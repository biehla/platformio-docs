..  Copyright (c) 2014-present PlatformIO <contact@platformio.org>
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
       http://www.apache.org/licenses/LICENSE-2.0
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

.. _cmd_remote:

PlatformIO Remote CLI
=====================

Helper command for :ref:`pioremote`.

To print all available commands and options use:

.. code-block:: bash

    pio remote --help
    platformio remote --help
    platformio remote COMMAND --help

    # run command on the specified PIO Remote Agents
    platformio remote --agent NAME_1 --agent NAME_N COMMAND


.. toctree::
    :maxdepth: 2

    cmd_agent
    cmd_device
    cmd_run
    cmd_test
    cmd_update
