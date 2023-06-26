###################################################
nsq_exporter - A simple prometheus exporter for nsq
###################################################

A prometheus exporter for `nsq <https://nsq.io/>`_ metrics. Stats are gathered
in JSON format from the `nsqd stats endpoint
<https://nsq.io/components/nsqd.html#get-stats>`_.

This simple exporter is meant to replace the `exporter
<https://github.com/lovoo/nsq_exporter>`_ that is referenced in the prometheus
`list of exporters
<https://prometheus.io/docs/instrumenting/exporters/#messaging-systems>`_.
I had issues with the exporter not working out of the box, lack of
documentation and metrics naming.

References
==========

* `nsqd HTTP API <https://nsq.io/components/nsqd.html#get-stats>`_

License
=======

mailgun-textfile-exporter is published under a BSD 3-clause license, see the
LICENSE file distributed with the project.
