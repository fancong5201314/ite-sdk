add_definitions(
    -DHAVE_CONFIG_H
    -DHAVE_FCNTL_H
    -DSRV_RECORD
    )

include_directories(
    .
    )

add_library(eXosip2 STATIC
    eXosip.c
    eXconf.c
    eXregister_api.c
    eXcall_api.c
    eXmessage_api.c
    eXtransport.c
    jrequest.c
    jresponse.c
    jcallback.c
    jdialog.c
    udp.c
    jcall.c
    jreg.c
    eXutils.c
    jevents.c
    misc.c
    jauth.c
    eXtransport.h
    eXosip2.h
    eXtl_udp.c
    eXtl_tcp.c
    eXtl_dtls.c
    eXtl_tls.c
    milenage.c
    rijndael.c
    milenage.h
    rijndael.h
    eXsubscription_api.c
    eXoptions_api.c
    eXinsubscription_api.c
    eXpublish_api.c
    jnotify.c
    jsubscribe.c
    jpipe.c
    jpipe.h
    jpublish.c
    sdp_offans.c
    )
