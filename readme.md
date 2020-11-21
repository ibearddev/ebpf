eBPF
-------
[![PkgGoDev](https://pkg.go.dev/badge/github.com/cilium/ebpf)](https://pkg.go.dev/github.com/cilium/ebpf)

eBPF - это чистая библиотека Go, которая предоставляет утилиты для загрузки, компиляции и отладки программ eBPF. Он имеет минимальные внешние зависимости и предназначен для использования в длительных процессах.

* [asm](https://pkg.go.dev/github.com/cilium/ebpf/asm) contains a basic assembler.
* [link](https://pkg.go.dev/github.com/cilium/ebpf/link) allows attaching eBPF to various hooks.
* [perf](https://pkg.go.dev/github.com/cilium/ebpf/perf) allows reading from a PERF_EVENT_ARRAY.
* [cmd/bpf2go](https://pkg.go.dev/github.com/cilium/ebpf/cmd/bpf2go) allows embedding eBPF in Go.

Библиотека поддерживается [Cloudflare](https://www.cloudflare.com) и [Cilium](https://www.cilium.io). 
## Статус

Пакет готов к продакшену, но **API нестабилен сейчас**. 
Ожидайте обновления своего кода, если хотите использовать пакет.

## Зависимости

* Последние версия go [с поддержкой upstream](https://golang.org/doc/devel/release.html#policy)
* Linux 4.9, 4.19 bkb 5.4 (промежуточные версии должны работать, но никто их не тестировал)

## Useful resources

* [eBPF.io](https://ebpf.io) (recommended)
* [Cilium eBPF documentation](https://docs.cilium.io/en/latest/bpf/#bpf-guide) (recommended)
* [Linux documentation on BPF](http://elixir.free-electrons.com/linux/latest/source/Documentation/networking/filter.txt)
* [eBPF features by Linux version](https://github.com/iovisor/bcc/blob/master/docs/kernel-versions.md)
