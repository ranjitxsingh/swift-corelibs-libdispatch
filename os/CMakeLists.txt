
# TODO(compnerd) ensure that object_private.h voucher_activity_private.h
# voucher_private.h are included in the source tarball

install(FILES
          object.h
          linux_base.h
        DESTINATION
          "${INSTALL_LIBDIR}/swift/os")

